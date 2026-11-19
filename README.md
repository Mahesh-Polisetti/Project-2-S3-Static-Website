# Project 2: Host a Static Website on Amazon S3 using Terraform

## Project Overview
This project demonstrates how to host a static website on Amazon S3 using Terraform.

## Technologies Used
- Amazon Web Services (AWS)
- Amazon S3
- Terraform
- HTML

## AWS Configuration
- Region: ap-south-1 (Mumbai)
- Bucket Name: mahesh-static-website-2026-unique
- Static Website Hosting: Enabled

## Project Files
- provider.tf - AWS provider configuration
- variables.tf - Terraform variables
- main.tf - AWS infrastructure resources
- outputs.tf - Website endpoint and bucket outputs
- index.html - Main website page
- error.html - Error page
- .gitignore - Files excluded from Git

## Deployment Steps

1. Initialize Terraform:
   terraform init

2. Format configuration:
   terraform fmt

3. Validate configuration:
   terraform validate

4. Preview infrastructure:
   terraform plan

5. Deploy infrastructure:
   terraform apply

## Website URL
http://mahesh-static-website-2026-unique.s3-website.ap-south-1.amazonaws.com

## Result
Successfully hosted a publicly accessible static website using Amazon S3 and Terraform.

## Cleanup
To delete the AWS resources:
terraform destroy
