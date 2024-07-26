# EdN-AWS-project


This repository contains the AWS architecture diagram for the IT infrastructure migration of Company X.

## AWS Architecture Diagram

![AWS Architecture Diagram](https://github.com/elvenj/EdN-AWS-project/blob/main/EdN-AWS-architecture.svg)

## Project Description

Company X, a large online retailer, is facing challenges with the scalability and availability of its current IT system. With the increase in online transactions and the expansion of its digital services, the company has decided to migrate to a cloud solution to improve the performance, security, and flexibility of its infrastructure.

### Objective

Migrate the IT infrastructure of Company X to the cloud, implementing a scalable and secure solution that supports future growth and enhances the customer experience.

### Architecture Components

- **Amazon S3:** Object storage for files and backups.
- **Amazon CloudFront:** CDN service to deliver content with low latency.
- **Elastic Load Balancer (ELB):** Load balancing to distribute traffic among EC2 instances.
- **Amazon VPC:** Network isolation for the company with public and private subnets.
- **Amazon EC2:** Instances to host applications.
- **Auto Scaling:** Automatic scalability of EC2 instances.
- **Amazon RDS:** Managed database for structured data storage.
- **Amazon CloudWatch:** Monitoring and logging of resources.
- **Amazon SNS:** Notification service for sending alerts and messages.

### Detailed Diagram

1. **Users:** Represents the end users accessing the application.
2. **Edge Location:** CloudFront point of presence to distribute content to users.
3. **Amazon S3:** Used to store static content.
4. **Elastic Load Balancer (ELB):** Distributes traffic to EC2 instances across availability zones.
5. **Availability Zones (AZ1 and AZ2):** EC2 instances distributed between two availability zones for high availability.
6. **Auto Scaling:** Configured to automatically scale EC2 instances according to demand.
7. **Amazon RDS:** Managed relational database.
8. **System Logs:** System logs stored and monitored.
9. **Amazon CloudWatch:** Monitoring service.
10. **Amazon SNS:** Notification service for alerts.

### How to Use

1. Clone the repository:
   ```sh
   git clone https://github.com/elvenj/EdN-AWS-project.git
