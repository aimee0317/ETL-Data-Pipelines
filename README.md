# ETL Data Pipelines

- Author: Amelia Tang

This is the GitHub repository to document various ETL data pipelines I designed for different projects. 

## What is ETL?
Extract, Transform and Load (ETL) us a fundamental framework for streamlining data processing workflows. ETL pipelines facilitate the efficient extraction of data from diverse sources, transformation into a usable format, and loading into designated destinations for analysis.

#### Extract 
This step involves gathering data from various sources such as databases, APIs, or files.

#### Transform 
In this step, the extracted data is cleaned, validated, and transformed into a consistent format suitable for analysis.

#### Load 
The transformed data is loaded into a target database or data warehouse, where it can be stored and accessed for further analysis or reporting.

## Project 1 (Python BeautifulSoup, AWS EC2, S3, Glue and Athena) 
#### ETL Diagrams
Extra public listing data from eBay.com using the Python script, transformed the data in AWS Glue and load the transformed data to AWS Athena for further analysis  

![](ETL_diagram.png)

#### ETL Data Pipeline Implementation on AWS  
To demonstrate the implementation of the ETL data pipelines on AWS, I have created blog posts on Medium.com to document the process.
- **Extract**: Run a Python web scrapping file stored in an S3 bucket on an EC2 instance and save the output csv file to the S3 bucket
 [Run a Python Script Stored in S3 on EC2](https://medium.com/@aimee.tang0317/beginners-guide-to-aws-how-to-run-a-python-script-stored-in-s3-on-ec2-f05730c500e7)
- **Transformation & Load**:
  Manipulate and transform the output csv file using AWS Glue and load the data to AWS Athena for query and analysis and save the result files to an S3 bucket 
[How to Create a Powerful ETL Data Pipeline with Python and AWS Services](https://medium.com/@aimee.tang0317/how-to-create-a-powerful-etl-data-pipeline-with-python-and-aws-services-6ad8ddd7ca1b)

## Project 2 (Databricks)
TBU
