# Cloud Security for Healthcare Application

## Overview
This project focuses on securing a cloud-hosted healthcare application using AWS security best practices. It covers key areas such as IAM access control, VPC security, AWS WAF for web protection, S3 encryption, RDS security, and automated backup strategies. The architecture is designed to mitigate cloud-based threats, enforce compliance (HIPAA, NIST), and ensure high availability using AWS services like EC2, S3, RDS, Route 53, CloudTrail, and GuardDuty.

## Repository Structure
- `midterm/` – Cloud security risk assessment and vulnerability analysis.
- `final/` – Proposed secure cloud architecture with AWS service integration.
- `architecture/` – AWS network and security architecture diagrams.
- `security-configs/` – IAM policies, firewall rules, VPC flow logs, and WAF configurations.
- `references/` – Compliance guidelines and AWS security documentation.

## Security Areas Covered
- **Identity and Access Management (IAM):** Role-based access control, MFA, and least privilege policies.
- **Network Security:** VPC segmentation, security groups, NACLs, and DNS firewall configurations.
- **Web Application Security:** AWS WAF, Shield, Route 53, and TLS implementation.
- **Data Protection:** S3 bucket security, object lock, and encryption of EBS and RDS instances.
- **Monitoring and Compliance:** AWS CloudTrail, GuardDuty, AWS Config, and security audits.
- **Disaster Recovery and High Availability:** Automated backups, Multi-AZ RDS, auto-scaling, and failover strategies.

## AWS Services Implemented
- **IAM** for access control and policy management.
- **VPC, Security Groups, NACLs** for network isolation.
- **AWS WAF, Shield, and Route 53** for web application security.
- **S3, RDS, and AWS KMS** for data encryption and storage security.
- **CloudTrail, GuardDuty, and CloudWatch** for real-time monitoring.
- **Auto Scaling, Load Balancer, and Backup Services** for availability and resilience.

For more details, refer to:
- [Cloud Security Risk Assessment](midterm/README_Midterm.md)
- [AWS Secure Architecture Implementation](final/README_Final.md)
