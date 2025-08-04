# AWSinfraautomation
AWS Infrastructure with Terraform and CI/CD Integration
Build a modular and reusable AWS infrastructure using Terraform, with CI/CD pipelines in Azure DevOps to manage deployments. This project reflects cloud automation, security, and scalability

# 🌐 AWS Infrastructure Automation with Terraform & Azure DevOps

This project showcases an automated AWS cloud setup using Terraform, integrated with CI/CD pipelines via Azure DevOps. It focuses on modular infrastructure, scalability, and security—ideal for DevOps roles emphasizing IaC and pipeline engineering.

## 🚀 Features
- Modular Terraform structure (VPC, EC2, S3, RDS)
- CI/CD pipeline using Azure DevOps YAML
- Role-based IAM policies
- Bootstrap scripting for EC2 initialization

## 🧰 Tech Stack
- **Terraform** (v1.0+)
- **AWS CLI**
- **Azure DevOps**
- **Bash**

## 🔧 Setup
1. Clone repo: `git clone https://github.com/naaz7860/aws-infra-terraform.git`
2. Navigate to env folder: `cd environments/dev`
3. Initialize Terraform: `terraform init`
4. Plan & apply: `terraform plan && terraform apply`
5. Monitor deployments via Azure DevOps pipeline.

## 📂 Structure

aws-infra-terraform/
├── modules/
│   ├── vpc/
│   ├── ec2/
│   ├── rds/
│   └── s3/
├── environments/
│   ├── dev/
│   └── prod/
├── pipelines/
│   └── azure-devops/
├── scripts/
│   └── bootstrap.sh
├── .gitignore
├── README.md
└── main.tf


## 📂 Structure
