# AWS Infrastructure Automation with CloudFormation

## Overview
This project demonstrates how to automate the provisioning of a complete AWS infrastructure using CloudFormation.

It creates a fully functional environment including networking, compute, and storage resources using a single YAML template, enabling consistent and repeatable deployments.

---

## Architecture

The CloudFormation template provisions:

- VPC (custom network)
- Public Subnet
- Route Table with internet access
- Security Group
- EC2 Instance
- S3 Bucket

---

## Key Features
- Infrastructure as Code (IaC) using CloudFormation
- Automated creation of AWS resources in a single stack
- Reusable and parameterized template
- Consistent and repeatable deployments
- Reduced manual configuration errors

---

## Technologies Used
- AWS CloudFormation
- YAML
- AWS EC2, S3, VPC

---

## Template Structure

- **Parameters** – Inputs provided at runtime  
- **Mappings** – Key-value pairs for dynamic configuration  
- **Resources** – Defines AWS infrastructure  
- **Outputs** – Displays useful information (e.g., instance details)

---

## Usage

1. Upload the template to AWS CloudFormation
2. Create a new stack
3. Provide required parameters
4. Launch the stack to provision resources automatically

---

![pic2-Page-5 drawio](https://github.com/sumathi1805/project2/assets/150107821/8a3c7090-d986-4c75-8884-4cb67a07611c)



## Key Highlights

- Implemented Infrastructure as Code (IaC) using CloudFormation to provision AWS resources
- Automated deployment of complete infrastructure including VPC, EC2, and S3
- Used parameterized templates for flexible and reusable deployments
- Managed resource orchestration through CloudFormation stacks
- Ensured consistent and repeatable environment setup
- Reduced manual configuration and minimized human errors
  
## Outcome
This project simplifies infrastructure deployment by automating the creation of AWS resources, ensuring consistency, scalability, and faster provisioning.

## ⚠️ Challenges & Learnings

### Challenges
- Debugging CloudFormation template errors due to incorrect YAML formatting
- Managing dependencies between resources like VPC, subnet, and EC2
- Handling stack failures and rollback scenarios

### Learnings
- Gained strong understanding of Infrastructure as Code (IaC)
- Learned how CloudFormation manages resource orchestration using stacks
- Improved ability to write reusable and parameterized templates

