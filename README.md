# Terraform 3-Tier Architecture

This project uses Terraform to deploy a 3-tier architecture on AWS. It includes a networking layer, application layer with EC2 and Auto Scaling, and a database layer with RDS.

---

## 📦 Features

- VPC, Subnets, Route Tables, NAT Gateway, Internet Gateway
- EC2 instances with Auto Scaling and Load Balancer
- IAM roles and instance profiles
- RDS database (MySQL)
- Ubuntu AMI lookup from Canonical (official ID: `099720109477`)
- Modular and reusable Terraform code

---

## 📁 Folder Structure

.
├── main.tf

├── providers.tf

├── outputs.tf

├── variables.tf

├── terraform.tfvars

├── versions.tf

└── modules/

├── networking/

├── autoscaling/

└── database/




