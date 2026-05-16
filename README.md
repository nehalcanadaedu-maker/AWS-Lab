🔐 AWS Cloud Security Lab

A hands-on cloud security lab built on Amazon Web Services (AWS) to simulate real-world security monitoring, logging, and incident detection scenarios. This project demonstrates practical skills in cloud security, SIEM integration, and threat detection.

📌 Project Overview

This lab focuses on building and securing a basic AWS environment while enabling logging, monitoring, and security analysis. It is designed for SOC analyst practice, cloud security learning, and portfolio demonstration.

You will learn how to:

Configure AWS IAM securely
Enable logging and monitoring using AWS CloudTrail & CloudWatch
Detect suspicious activity in AWS environments
Simulate security incidents
Analyze logs for threat hunting

🏗️ Architecture
AWS EC2 (Linux/Windows instance)
IAM Users & Roles
AWS CloudTrail (API logging)
Amazon CloudWatch (monitoring & alerts)

⚙️ Setup Instructions
1. Create AWS Free Tier Account
Sign up at: https://aws.amazon.com/free
2. Configure IAM
Create a new IAM user
Enable MFA (Multi-Factor Authentication)
Assign least privilege permissions (avoid admin access where possible)
3. Launch EC2 Instance
Choose Ubuntu or Windows Server
Allow only required ports (SSH 22 / RDP 3389)
Attach IAM role if needed
4. Enable Logging
CloudTrail
Enable CloudTrail for all regions
Send logs to S3 bucket
CloudWatch
Create log groups
Monitor:
Login attempts
EC2 activity
API calls


