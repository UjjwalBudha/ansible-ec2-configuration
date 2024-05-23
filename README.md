# Ansible EC2 Instance Configuration

This repository contains scripts and playbooks for configuring an EC2 instance using Ansible. The tasks include installing Nginx/Apache, deploying a Node/Django/PHP application, configuring the server using Jinja templates, and utilizing dynamic inventory.

## Prerequisites

- **AWS Account**: Ensure you have an AWS account with necessary permissions.
- **Ansible**: Install Ansible on your local machine.
- **AWS CLI**: Configure the AWS CLI with your IAM user credentials.
- **EC2 Key Pair**: Ensure you have an EC2 key pair for SSH access to instances.

## Repository Structure

- **terraform**: Contains Terraform scripts for provisioning EC2 instances.
- **ansible**: Contains Ansible playbooks and roles for configuring the EC2 instances.
