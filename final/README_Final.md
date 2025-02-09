# AWS Secure Architecture for Healthcare Application

## Overview
This report presents a **secure AWS architecture** to mitigate security risks identified in the cloud-hosted healthcare system. It focuses on **network security, IAM control, data protection, and availability**.

## Key AWS Security Enhancements
### **Identity & Access Management (IAM)**
- Implement **least privilege access** with IAM roles and policies.
- Enforce **multi-factor authentication (MFA)** for all users.
- Use **AWS Secrets Manager** to secure API keys and credentials.

### **Network Security**
- Implement **VPC segmentation** to isolate sensitive workloads.
- Configure **security groups and NACLs** to restrict traffic flow.
- Enable **VPC Flow Logs** for real-time traffic monitoring.

### **Web Application Security**
- Deploy **AWS WAF** to mitigate web-based attacks (XSS, SQLi).
- Use **AWS Shield Advanced** for DDoS protection.
- Route traffic securely with **AWS Route 53 and TLS encryption**.

### **Data Protection**
- Encrypt **S3, EBS, and RDS** using **AWS KMS-managed keys**.
- Enable **object versioning and access logging** for all S3 buckets.
- Use **Multi-AZ RDS deployment** for database high availability.

### **Compliance & Monitoring**
- Enable **AWS Config and GuardDuty** for compliance monitoring.
- Use **AWS CloudTrail** to track account activity logs.
- Deploy **AWS Security Hub** to assess security posture.

For a complete architectural design, refer to the [Final Report](Final_Report.pdf).
