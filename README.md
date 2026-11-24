SWYNEX – Cloud Architecture Outline

Project Overview

This project presents a conceptual AWS-based serverless architecture for a Product Catalog Web Application.

The objective is to understand how cloud computing services work together to build a scalable, secure, and reliable web application.

Project Objectives

- Understand cloud computing architecture.
- Identify compute, storage, and networking components.
- Understand Identity and Access Management (IAM).
- Explore AWS serverless services.
- Understand cloud security and monitoring.

## AWS Services Used

| AWS Service | Purpose |
|---|---|
| Amazon S3 | Stores website files and images |
| Amazon CloudFront | Delivers website content |
| Amazon API Gateway | Manages API requests |
| AWS Lambda | Executes application code |
| Amazon DynamoDB | Stores product information |
| AWS IAM | Manages access and permissions |
| Amazon CloudWatch | Monitors logs and metrics |
Architecture Components

1. Compute

AWS Lambda executes backend application code without requiring server management.

2. Storage

Amazon S3 stores static website files, while DynamoDB stores product records.

3. Networking

Amazon CloudFront delivers website content, and API Gateway handles application API requests.

4. Identity and Access Management

AWS IAM controls access to cloud resources using permissions and policies.

Security Considerations

- Apply least-privilege access.
- Protect AWS account credentials.
- Restrict access to storage resources.
- Monitor application activity.

Monitoring

Amazon CloudWatch can collect logs and metrics and support monitoring alerts.

Cost Considerations

- Monitor AWS resource usage.
- Review service pricing before deployment.
- Avoid unnecessary running resources.
- Set billing alerts where available.

Project Status

In Progress – Conceptual Architecture Design.

Internship Information

Organization: SWYNEX Technologies
Internship Domain: Cloud Computing
Task: Task 1 – Cloud Architecture Outline

Author

Yogiraj Solanki

GitHub: yogirajsolanki3157-byte
