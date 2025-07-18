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

---

## Initialize Terraform
terraform init

## Preview the infrastructure changes
terraform plan

## Apply the configuration and create infrastructure
terraform apply

## Destroy the infrastructure when no longer needed
terraform destroy


![image](https://github.com/user-attachments/assets/f6d15d76-7dbe-41a7-baf9-f58b6772d4a2)


![image](https://github.com/user-attachments/assets/9fa75c30-f38e-4c19-9ee2-089eba86f077)


