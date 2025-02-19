# landingzone-aws-terraform

This repository provides Terraform code to set up an AWS Landing Zone using AWS Organizations. It automates the creation of AWS accounts, security controls, and organizational units to establish a secure multi-account AWS environment.

## Features

- **AWS Organizations**: Centralized account management
- **Multi-Account Structure**: Creates management, security, log archive, and shared services accounts
- **Security Baseline**: Establishes security best practices
- **Scalability**: Easily extendable and customizable

## Prerequisites

- Terraform >= 1.0.0
- AWS CLI configured with necessary permissions
- IAM permissions to manage AWS Organizations, accounts, and security services

## Terraform Modules

- **organization**: Manages AWS Organizations setup
- **accounts**: Creates and manages AWS accounts within the organization
- **security**: Configures security policies and guardrails

## Usage

### Clone the Repository:

```bash
git clone https://github.com/devopscodelab/landingzone-aws-terraform.git
cd aws-landing-zone
