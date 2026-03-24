# 🚀 AWS 3-Tier Infrastructure Automation (Terraform)

## 📌 Project Overview
This project automates the provisioning of a highly available and scalable 3-tier architecture on AWS using Terraform.

---

## 🏗️ Architecture

Client → ALB → Web Tier → App Tier → Database Tier

- Public Subnet: Load Balancer
- Private Subnet: Application Servers
- Database Subnet: RDS / DB Layer

---

## ⚙️ Tech Stack

- Cloud: AWS
- IaC: Terraform
- Load Balancer: Application Load Balancer (ALB)
- Compute: EC2 + Auto Scaling
- Networking: VPC, Subnets, IGW, NAT Gateway

---

## 📁 Project Structure


modules/
network/
compute/
database/
main.tf
variables.tf
outputs.tf


---

## 🚀 Features

- Fully automated infrastructure provisioning
- Highly available architecture
- Auto Scaling for high traffic
- Secure VPC design (public/private subnets)

---

## 🔐 Security Best Practices

- Private subnets for backend & DB
- Security Groups for controlled access
- NAT Gateway for outbound traffic

---

## 🔥 Challenges & Fixes

- Fixed dependency issues in Terraform modules
- Managed state file properly
- Handled ALB target group configuration

---

## 📌 Future Improvements

- Add Terraform remote backend (S3 + DynamoDB)
- Integrate CI/CD pipeline
- Add monitoring (CloudWatch)

---

## 👨‍💻 Author

Hariharan B