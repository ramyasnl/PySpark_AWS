# PySpark_Challenge Module 16 
ETL and analysis of Amazon Vine reviews with AWS, postgresql, PySpark, and Google Colab
#<b>About this Project</b> 
In this project, we have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products.</br> We’ll need to pick one of these datasets from S3 and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data through pgAdmin. </br>Next, We’ll use PySpark to determine if there is any bias toward favorable reviews from Vine members in our dataset. Then, We’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.</br>
BLOCK DIAGRAM </br>
#<b>Results</b>
#Amazon_Reviews_ETL </br>
* The S3 link, I took is "https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Wireless_v1_00.tsv.gz this is going to be my data set </br>
* We’ll create an AWS RDS database with tables in pgAdmin, use the dataset from the Amazon Review datasets and extract the dataset into a DataFrame</br>
* Next,we transform the DataFrame into four separate DataFrames that match the table schema in pgAdmin. </br>
* Then, we'll upload the transformed data into the appropriate tables and run  queries in pgAdmin to confirm that the data has been uploaded.</br>
#customers_table  </br>
LINK TO CUSTOMER TAB </br>
#products_table</br>
LINK TO CUSTOMER TAB </br>
#review_id_table</br>
LINK TO CUSTOMER TAB </br>
#vine_table </br>
LINK TO CUSTOMER TAB </br>
#<b>Summary</b>
LINK TO vine DF </br>
LINK TO paidvine DF </br>
LINK TO unpaidvine DF </br>

Total_paid_number:</br>
613</br>
Paid_five_star_number:</br>
222</br>
Percentage_five_star_vine:</br>
0.3621533442088091</br>
