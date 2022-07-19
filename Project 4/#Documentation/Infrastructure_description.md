# Infrastructure

Using AWS services to host and run full stack project  

## RDS

Relational Database Service to run Postgres database instance

## Elastic Beanstalk

Elastic Beanstalk creates an EC2 instance, security group and also runs the application code for our backend application. Platform is Node.js 16 running on 64bit Amazon Linux 2/5.5.4.

## S3

Used to create 2 buckets: first bucket to host posts media with publicly accessible files, second one to host front end static website