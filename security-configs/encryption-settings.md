# AWS Encryption Best Practices

## Overview
Encryption is used to protect sensitive healthcare data stored in AWS **S3, EBS, and RDS**.

## S3 Encryption
- Enable **Server-Side Encryption (SSE-S3, SSE-KMS)**.
- Use **S3 Bucket Policies** to enforce encryption.
- Enable **S3 Object Lock** to prevent modification.

## EBS Encryption
- Encrypt all **EBS volumes** using **AWS KMS**.
- Use **IAM permissions** to restrict encryption key access.

## RDS Encryption
- Enable **RDS storage encryption** for database instances.
- Use **AWS Secrets Manager** for credential management.

## Best Practices
- Rotate encryption keys regularly.
- Monitor encryption compliance using **AWS Config**.
- Restrict access to KMS keys using IAM policies.
