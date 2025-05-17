# AWS-ASSIGNMENT

*QUESTIONS OF AWS ASSIGNMENT*
* Explain the difference between AWS Regions, Availability Zones, and Edge Locations. Why is this important for data analysis and latency-sensitive applications"
* Using the AWS CLI, list all available AWS regions. Share the command used and the output.
* Create a new IAM user with least privilege access to Amazon S3. Share your attached policies (JSON or screenshot).
* Compare different Amazon S3 storage (Standard, Intelligent-Tiering, Glacier). When should each be used in data analytics workflows".
* Create an S3 bucket and upload a sample dataset (CSV or JSON). Enable versioning and show at least two versions of one file.
* Write and apply a lifecycle policy to move files to Glacier after 30 days and delete them after 90. Share the policy JSON or Screenshot.
* Compare RDS, DynamoDB, and Redshift for use in different stages of a data pipeline. Give one use case for each.
* Create a DynamoDB table and insert 3 records manually. Then write a Lambda function that adds records when triggered by S3 uploads.
* What is serverless computing? Discuss pros and cons of using AWS Lambda for data pipelines.
* Create a Lambda function triggered by S3 uploads that logs file name, size, and timestamp to Cloudwatch. Share code and a log screenshot.
* Use AWS Glue to crawl your S3 dataset, create a Data Catalog table, and run a Glue job to convert CSV data to parquet. Share job code and output location.
* Explain the difference between Kinesis Data Streams, Kinesis Firehose, and Kinesis Data Analytics. Provide a real-world example of how each would be used.
* What is columnar storage and how does it benefit Redshift performance for analytics workloads".
* Load a CSV file from S3 into Redshift using the COPY command. Share table schema, command used, and sample output from a query.
* What is the role of the AWS Glue Data Catalog in Athena? How does schema-on-read work?
* Create an Athena table from S3 data using Glue Catalog. Run a query and share the SQL + result screenshot.
* Describe how Amazon Quicksight supports business intelligence in a serverless data architecture. What are SPICE and embedded dashboards?
* Connect Quicksight to Athena or Redshift and build a dashboard with at least one calculated field and one filter. Share a screenshot of your final dashboard.
* Explain how AWS CloudWatch and CloudTrail differ. IN a data analytics pipeline, what role does each play in monitoring, auditing, and troubleshooting?
* Describe a complete end-to-end data analytics pipeline using AWS services. Include services for data ingestion, storage, transformation, querying, and visualization. (Example: S3 → Lambda → Glue → Quicksight). Explain why you would choose each service for the stage it’s used in.
