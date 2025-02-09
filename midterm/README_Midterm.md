# Cloud Security Risk Assessment

## Overview
The midterm report presents a security risk assessment for a cloud-hosted healthcare application. It identifies infrastructure vulnerabilities, their potential impact, and mitigation strategies using AWS security services.

## Identified Security Risks
- **Excessive IAM Permissions:** Misconfigured policies allowing unnecessary access.
- **Unprotected S3 Buckets:** Public exposure of sensitive healthcare data.
- **Unencrypted EBS Volumes:** Potential for data leaks due to unprotected storage.
- **Lack of Network Segmentation:** VPC misconfigurations leading to lateral movement risks.
- **Weak Web Security:** No AWS WAF or Shield protections against DDoS and OWASP Top 10 attacks.

## Proposed Security Improvements
- **IAM Hardening:** Implement role-based access control (RBAC) and enforce MFA.
- **S3 Security:** Enable server-side encryption, restrict public access, and use S3 bucket policies.
- **Storage Encryption:** Encrypt EBS volumes and enforce AWS KMS-based encryption.
- **VPC Security:** Define security groups and NACLs for segmenting workloads.
- **Web Security:** Deploy AWS WAF, AWS Shield, and Route 53 for web protection.

For a detailed risk analysis, refer to the [Midterm Report](Midterm_Report.pdf).
