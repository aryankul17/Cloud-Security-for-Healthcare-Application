# IAM Policies for Least Privilege Access

## Overview
This IAM policy restricts access based on the principle of **least privilege**, ensuring users and services have only the permissions required for their role.

## Example IAM Policy for S3 Read-Only Access
```json
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Effect": "Allow",
            "Action": [
                "s3:GetObject",
                "s3:ListBucket"
            ],
            "Resource": [
                "arn:aws:s3:::secure-healthcare-data",
                "arn:aws:s3:::secure-healthcare-data/*"
            ]
        }
    ]
}
