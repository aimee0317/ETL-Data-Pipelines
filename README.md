# Python ETL Data Pipeline with AWS using eBay Web Scraping Public Data

- Author: Amelia Tang

### Extract 
Run a Python web scrapping file stored in an S3 bucket on an EC2 instance and save the output csv file to the S3 bucket

### Transform 
Manipulate and transform the output csv file using AWS Glue

### Load 
Load the data to AWS Athena for query and analysis and save the result files to an S3 bucket 

### ETL Diagram 
![](ETL_diagram.png)

### Creating the ETL data pipeline on AWS 
I documented the process of creating the ETL pipeline on Medium. 
<br>- Extract: [Run a Python Script Stored in S3 on EC2](https://medium.com/@aimee.tang0317/beginners-guide-to-aws-how-to-run-a-python-script-stored-in-s3-on-ec2-f05730c500e7)
<br>- Transformation & Load: [How to Create a Powerful ETL Data Pipeline with Python and AWS Services](https://medium.com/@aimee.tang0317/how-to-create-a-powerful-etl-data-pipeline-with-python-and-aws-services-6ad8ddd7ca1b)
