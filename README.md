# `Amazon_Vine_Analysis`

## `Project Overview ` <br/>
The purpose of Amazon_Vine_Analysis is to analyze Amazon reviews written by members of the paid Amazon Vine program. <br/>
In this project, I had  access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. I picked Shoes dataset and used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. After that, I used PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in Shoes dataset. <br/>
Then, I  wrote a summary of the analysis for Jennifer to submit to the SellBy stakeholders. <br/>
#### Resources <br/>
• Data Source: [Google](https://www.google.com/), [Amazon Review Dataset]( https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt) <br/> 
•	Software: PySpark, AWS RDS, pgAdmin, SQL, Git Bash, GitHub. <br/>

# `Summary ` <br/>

### 1. Performing ETL on Amazon Product Reviews
Using my knowledge of the cloud ETL process, I created an AWS RDS database with tables in pgAdmin, picked a “Shoes” dataset from the Amazon Review datasets Links to an external site., and extracted the dataset into a DataFrame. I transformed the DataFrame into four separate DataFrames that match the table schema in pgAdmin. Then, I uploaded the transformed data into the appropriate tables and ran queries in pgAdmin to confirm that the data has been uploaded. <br/>
#### The customers_table          and  The products_table <br/>

<img src="https://user-images.githubusercontent.com/110998103/204059728-9ac29d3e-b2b5-4d88-a7be-740dd5960e5d.png" width=30% height=30%>   <img src="https://user-images.githubusercontent.com/110998103/204059791-f6f0fb94-e7af-4bbb-a383-a853b3269e75.png" width=40% height=40%>



#### The review_id_table     and     The vine_table <br/>


<img src="https://user-images.githubusercontent.com/110998103/204059845-061729bd-9283-49e1-9dc4-90e810a4d023.png" width=45% height=50%> <img src="https://user-images.githubusercontent.com/110998103/204059803-9b3d41e3-5cf2-46b5-ad52-9cbe5a34ab8c.png" width=50% height=50%>

