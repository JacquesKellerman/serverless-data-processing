# Serverless Data Processing

## Overview
Uses AWS services to process real-time data streams in a serverless architecture

1. Dashboard app to process and visualize IOT data in real-time
2. Lambda functions to process real-time streams and persist in DynamoDB 
3. Amazon Kinesis Data Analytics used for a serverless application to aggregate data
4. Amazon Kinesis Data Firehose used to archive the raw data to Amazon S3
5. Athena to run ad-hoc queries against this raw data using SQL

AWS services used: Amazon Kinesis, AWS Lambda, Amazon S3, Amazon DynamoDB, Amazon Cognito, and Amazon Athena. 

## Architecture

![Architecture drawio](https://user-images.githubusercontent.com/97241128/170883526-00077020-ced7-443f-af5f-3a36d6cf73b8.png)
