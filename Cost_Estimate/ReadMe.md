# Cost Estimate for AWS Academy Cloud Architecting Capstone Project

## Project Overview  
This repository contains the cost estimate for the Cloud Architecting Capstone Project. The goal is to design a scalable, cost-effective cloud architecture using AWS services while adhering to the Well-Architected Framework.

## Estimated Monthly Cost Breakdown  

| **Service**            | **Usage**                       | **Estimated Cost (USD)** |
|-------------------------|----------------------------------|--------------------------|
| Amazon EC2             | 3 t3.micro instances (750 hours)| $22.32                  |
| Amazon S3              | 50 GB storage + 10,000 requests | $7.00                   |
| Amazon RDS             | db.t3.micro instance            | $13.82                  |
| Amazon CloudFront      | 1 TB data transfer              | $85.00                  |
| AWS Lambda             | 1 million invocations           | $0.20                   |
| Amazon Route 53        | 3 hosted zones + 100 queries    | $1.50                   |
| **Total Estimated Cost** | **N/A**                       | **$129.84/month**       |

## Cost Optimization Considerations  
- Use **Free Tier** wherever possible.  
- Optimize S3 by enabling lifecycle policies for older objects.  
- Leverage **Spot Instances** for non-critical workloads.  
- Enable **AWS Cost Explorer** for real-time monitoring.  

## Disclaimer  
This cost estimate is approximate and may vary based on actual usage and AWS pricing updates. Check the [AWS Pricing Calculator](https://calculator.aws) for detailed calculations.  
