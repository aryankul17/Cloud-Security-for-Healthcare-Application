# AWS WAF Security Configuration

## Overview
AWS Web Application Firewall (WAF) is used to protect the **healthcare application** from **web-based threats**, including **SQL injection (SQLi), cross-site scripting (XSS), and DDoS attacks**. It helps mitigate **malicious traffic** and ensures **application security and compliance**.

## AWS WAF Security Rules
- **SQL Injection Prevention** – Blocks SQLi attack patterns.
- **XSS Prevention** – Filters out cross-site scripting attempts.
- **Geo-restriction** – Limits access to trusted countries.
- **Rate Limiting** – Prevents excessive API requests from abusive sources.

## AWS WAF Configuration Steps
1. Navigate to **AWS WAF Console** in the AWS Management Console.
2. Click **Create WebACL** and attach it to **CloudFront, ALB, or API Gateway**.
3. Add **AWS Managed Rule Groups** to cover **OWASP Top 10 vulnerabilities**.
4. Define **custom rules** for SQLi, XSS, and IP filtering based on security needs.
5. Enable **AWS Shield Advanced** for **DDoS protection and automatic threat mitigation**.
6. Set up **logging** with **AWS CloudWatch** for monitoring blocked requests.

## Best Practices for AWS WAF
- Enable **real-time monitoring** with **AWS Security Hub**.
- Regularly **update and test custom WAF rules** to prevent new attack vectors.
- Implement **IP reputation lists** to block malicious actors.
- Integrate **AWS WAF with AWS Lambda** for automated security responses.

## Additional Resources
- AWS Documentation: [AWS WAF Overview](https://docs.aws.amazon.com/waf/latest/developerguide/)  
- AWS Shield: [DDoS Protection with AWS Shield](https://aws.amazon.com/shield/)  

