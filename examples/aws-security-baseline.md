# AWS Security Baseline

Example security considerations for a new AWS account.

Core controls:

CloudTrail enabled

VPC flow logs

IAM least privilege roles

Centralized logging

Encryption for storage services

Recommended layout:

AWS Organization
  Security Account
  Shared Services Account
  Workload Accounts

Security practices:

Avoid long-lived access keys

Use IAM roles instead of users where possible

Enable guardrails using SCPs

Monitor unusual API activity
