# Terraform Scripts — Cloud Infrastructure Automation

A collection of **Terraform** scripts and guides for automating cloud infrastructure deployment, scaling microservices with Docker and Kubernetes, and managing servers on AWS.

## Overview

This repository contains Infrastructure as Code (IaC) resources covering:
- Automated server provisioning with Terraform
- Scaling microservices architectures using Docker and Kubernetes
- Production deployment automation scripts

## Contents

| Document | Description |
|----------|-------------|
| `Terraform Script for Automation.pdf` | Automating cloud resource provisioning end-to-end |
| `Terraform Script for Server Deployment.pdf` | Deploying and managing servers with Terraform |
| `Scaling Microservices with Docker and Kubernetes.pdf` | Container orchestration patterns for microservices |

## Key Topics

### Terraform Automation
- Writing HCL (HashiCorp Configuration Language) modules
- Managing state files with remote backends (S3 + DynamoDB)
- Variable management and `tfvars` files
- Provisioning EC2 instances, VPCs, security groups, and more

### Server Deployment
- Bootstrapping servers with user data scripts
- Auto Scaling Groups and Launch Templates
- Blue/green deployments using Terraform

### Scaling Microservices
- Containerizing services with Docker
- Kubernetes deployments, services, and ingress rules
- Horizontal Pod Autoscaling (HPA)
- Managing container images with Amazon ECR

## Basic Terraform Workflow

```bash
terraform init       # Initialize providers and backend
terraform plan       # Preview changes
terraform apply      # Apply infrastructure changes
terraform destroy    # Tear down resources
```

## Technologies

| Technology | Purpose |
|------------|---------|
| Terraform | Infrastructure as Code |
| AWS | Cloud provider (EC2, VPC, S3, EKS) |
| Docker | Application containerization |
| Kubernetes | Container orchestration |
| Amazon EKS | Managed Kubernetes on AWS |

## Author

**Raj Bhoge** — Cloud & AI Engineer  
[GitHub](https://github.com/RajBhoge) | [LinkedIn](https://www.linkedin.com/in/raj-bhoge-834280194/) | [Blog](https://rajbhoge2107.hashnode.dev/)
