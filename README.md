# AWS Infrastructure Automation using Terraform and Ansible

This project demonstrates provisioning and configuration of cloud infrastructure using DevOps tools.

## Tools & Technologies
- AWS EC2
- Terraform (Infrastructure as Code)
- Ansible (Configuration Management)
- Linux
- Docker
- Git & GitHub

## Project Architecture

Local Machine  
→ Terraform provisions AWS EC2  
→ Terraform outputs public IP  
→ Ansible connects via SSH  
→ Docker installed automatically  
→ Nginx container deployed  

## How to Use

1. Clone this repository:
```bash
git clone <your-repo-url>
cd aws-terraform-ansible
