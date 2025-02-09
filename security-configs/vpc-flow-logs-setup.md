# VPC Flow Logs Configuration

## Overview
AWS VPC Flow Logs enable **network traffic monitoring** and provide **visibility into security events**.

## Steps to Enable VPC Flow Logs
1. **Go to AWS Console** → Navigate to **VPC Dashboard**.
2. **Select the VPC** you want to monitor.
3. Click **"Create Flow Log"** and choose **CloudWatch Logs or S3** as the destination.
4. Select **IAM Role** with permissions to publish logs.
5. Apply **filters** to capture **accepted/rejected traffic**.

## Best Practices
- Store logs in **AWS S3 with lifecycle policies**.
- Integrate logs with **AWS GuardDuty & AWS Security Hub**.
- Enable **real-time monitoring using CloudWatch Metrics**.
