# Secure Terraform Project Structure

A consistent Terraform structure helps maintain security and operational clarity.

Example layout:

terraform/
  modules/
  environments/
  shared/
  policies/

modules/
Reusable infrastructure components such as VPC, IAM roles, logging, and encryption resources.

environments/
Environment-specific configurations such as dev, staging, and production.

shared/
Common resources shared across environments.

policies/
Policy-as-code rules or guardrails applied during CI/CD validation.

Key principles:

Least privilege IAM roles

Separate state files per environment

Secure remote state storage

Code review before infrastructure changes

Automated security scanning of Terraform code
