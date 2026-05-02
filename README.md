
# Roboshop Infrastructure Provisioning (Dev Environment)

This repository demonstrates provisioning of infrastructure for the **Roboshop microservices application** using Infrastructure as Code (IaC).

The project focuses on automating the creation and management of cloud resources required to deploy a scalable and production-like environment.

---

## Project Overview

Roboshop is a **microservices-based e-commerce application** consisting of multiple services such as:

- Web (Frontend)
- Catalogue
- User
- Cart
- Shipping
- Payment
- Dispatch

These services require infrastructure components like servers, databases, and networking, which are provisioned automatically using IaC tools.

---

## What is Infrastructure as Code?

Infrastructure as Code (IaC) allows you to define and manage infrastructure using code instead of manual setup.

Tools like Terraform help automate provisioning, making infrastructure:

- Repeatable
- Scalable
- Version-controlled

IaC reduces human error and improves deployment consistency.
---

## Tech Stack

- Terraform
- Cloud Platform (AWS / similar)
- Linux
- Git & GitHub

---

## Architecture

The infrastructure includes:

- Virtual Machines (EC2 instances)
- Networking (VPC, Subnets, Security Groups)
- Databases (MongoDB, MySQL, Redis)
- Load balancing (optional)

Each Roboshop service runs on provisioned infrastructure, forming a complete multi-tier architecture.
---

## Key Features

- Automated infrastructure provisioning
- Modular Terraform design
- Scalable environment setup
- Reusable infrastructure components
- Version-controlled infrastructure

---

## Setup & Execution

1. Install Terraform

```bash
sudo apt update
sudo apt install terraform -y
```

---

2. Initialize Terraform

```bash
terraform init
```

---

3. Validate Configuration

```bash
terraform validate
```

---

4. Plan Infrastructure

```bash
terraform plan
```

---

5. Apply Changes

```bash
terraform apply
```

---

6. Destroy Infrastructure (Optional)

```bash
terraform destroy
```

---

## Learning Outcomes

Through this project, I gained hands-on experience in:

- Writing Terraform configurations
- Provisioning cloud infrastructure
- Designing scalable environments
- Managing infrastructure lifecycle

---

## Future Enhancements

- Add multi-environment support (dev, staging, prod)
- Integrate CI/CD pipelines
- Add remote state management (S3 + DynamoDB)
- Implement autoscaling & load balancers

---

## Note

This project is part of my DevOps learning journey, focusing on real-world infrastructure automation for microservices-based applications.
