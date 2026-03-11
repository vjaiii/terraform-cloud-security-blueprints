# GCP Secure Project Baseline

A minimal secure starting point for new GCP projects.

Core components:

Project-level IAM roles

Cloud Audit Logs enabled

VPC network with restricted firewall rules

Private service access where possible

Centralized logging export

Example structure:

Organization
  Folder
    Project
      VPC
      IAM policies
      Logging sinks
      Monitoring alerts

Security considerations:

Avoid overly broad roles such as Owner or Editor

Enable data access audit logs

Use service accounts with minimal permissions

Use private networking for internal services
