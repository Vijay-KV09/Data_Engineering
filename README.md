**Overview**
This project focuses on analyzing trending data from YouTube using a dataset from Kaggle. 
The data is processed and managed using AWS services such as S3 and Glue. Metadata is extracted to create tables for further analysis.  
**Project Workflow**  
  
**1.Data Collection:**

Downloaded YouTube trending dataset from Kaggle.
The dataset contains JSON files representing YouTube video trends.
  
**2.Data Storage:**

Uploaded the dataset to an AWS S3 bucket for centralized storage and accessibility.
  
**3.Data Processing with AWS Glue:**

Created an AWS Glue Crawler to automatically extract metadata from the uploaded JSON files.
The crawler scans the data and identifies the schema to generate tables for analysis.
  
**4.Table Creation:**

Tables were created in the AWS Glue Data Catalog using the schema extracted by the crawler.
The schema includes details such as video title, category, view count, likes, dislikes, and other metadata fields from the YouTube dataset.
  
**5.Table Schema Overview:**

The table schema represents the structure of the YouTube dataset, with columns mapping to key attributes like video ID, title, 
trending date, and engagement metrics (views, likes, dislikes, etc.).

  
**Tools and Technologies Used:**
AWS S3: For storing the dataset.
AWS Glue: For creating crawlers and extracting metadata to generate tables.
Kaggle: Source of the YouTube trend dataset.

  
**Next Steps:**
Further analysis and transformation of the data using AWS Glue, and integration with AWS Athena or other data querying tools.
