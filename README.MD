AWS Scalable Architecture Project

Project Overview
This project focuses on building a scalable and reliable AWS cloud architecture using Infrastructure as Code (IaC).
The goal was to automate every stage of deployment — from networking setup to compute, storage, and serverless integration — by using tools such as Terraform, AWS CloudFormation, and Boto3 (Python SDK).
It’s a hands-on implementation that brings together multiple AWS services to create a real-world, automated cloud environment.

Architecture Components
Here’s what the setup includes:
 VPC with public and private subnets for network isolation
 Internet Gateway & Route Tables for connectivity
 EC2 instances launched through CloudFormation templates
 RDS MySQL Database hosted securely in a private subnet
 Lambda function triggered by S3 file uploads (serverless logging)
 Auto Scaling Group and Load Balancer for managing web server load
 AWS CLI & Python (Boto3) scripts to automate cloud operations

 Together, these components form a flexible, fault-tolerant, and cost-efficient AWS infrastructure.

Tools and Technologies
AWS Services: EC2 | RDS | Lambda | S3 | CloudWatch
IaC Tools: Terraform | CloudFormation
Programming: Python (Boto3)
Other Tools: AWS CLI | GitHub

 Included Files
 AWS Project.pdf — full implementation report with architecture diagrams and setup steps

 Key Learning Outcomes
Through this project, I learned how to:
Design and deploy networking infrastructure using Terraform
Automate EC2, RDS, and Lambda deployments with CloudFormation templates
Build Lambda triggers to capture S3 events and log them in CloudWatch
Configure auto scaling and load balancing to handle traffic efficiently
Interact with AWS services using AWS CLI commands and Python Boto3 scripts

Overall, this project strengthened my understanding of cloud automation, infrastructure orchestration, and AWS best practices.

GitHub Portfolio Link
Visit My GitHub Profile – Akanksha576
