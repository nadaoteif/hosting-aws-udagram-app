
# Udagram Infrastructure 

## Diagram
![Infrastructure  Diagram](https://i.ibb.co/nj0PSm8/Infrastructure-Digram.png)


## Description

- RDS:
The database PostgreSQL is hosting on AWS RDS. So, Udagram-Api uses AWS RDS to stores and retrieves information.


- Elastic Beanstalk: 
The backend (Udagram-Api) is hosting on AWS Elastic Beanstalk service (EBS). Udagram-Api application will convert the application to zip file. This zip will upload to S3 bucket and the EBS will extract the application and run the Udagram-Api.


- S3 Bucket:

The frontend (Udagram-frontedn) is built and hosting on AWS S3 bucket. The S3 bucket must be public. From the URL that will create when upload the frontend the user can open the application.

Fronend URL: http://udagram-bucket-data99.s3-website-us-east-1.amazonaws.com
