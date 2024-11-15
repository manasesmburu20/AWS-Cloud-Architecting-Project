# Cost Estimate for AWS Academy Cloud Architecting Capstone Project

## Project Overview
This repository contains the cost estimate for the Cloud Architecting Capstone Project. The goal is to design a scalable, cost-effective cloud architecture using AWS services while adhering to the Well-Architected Framework.

## Updated Monthly Cost Breakdown

| **Service**              | **Usage**                              | **Estimated Cost (USD)** |
|--------------------------|-----------------------------------------|--------------------------|
| Amazon EC2               | 2 t3.micro instances (750 hours each)  | $15.18                   |
| Amazon RDS for MySQL     | 1 db.t3.micro instance (Multi-AZ, 20GB SSD) | $29.42               |
| Elastic Load Balancing   | 1 Application Load Balancer            | $18.47                   |
| AWS Secrets Manager      | 1 secret, 10 API calls/month           | $0.40                    |
| **Total Estimated Cost** | **N/A**                                | **$63.47/month**         |

## Cost Optimization Considerations
- Continue leveraging **Free Tier** benefits where applicable.
- Implement **Spot Instances** for non-critical workloads to reduce EC2 costs.
- Use **Reserved Instances** or **Savings Plans** for consistent workloads for further cost reductions.
- Utilize **AWS Cost Explorer** and **Budgets** for real-time cost tracking.

## Disclaimer
This cost estimate is approximate and may vary based on actual usage and AWS pricing updates. Check the [AWS Pricing Calculator](https://calculator.aws) for the most accurate and detailed calculations.


