
# AWS 3-Tier Scalable & Secure Infrastructure Project

## 📌 Project Overview
This project demonstrates the implementation of a *3-tier scalable and secure infrastructure on AWS* using core DevOps and cloud services.  
The architecture is designed to handle real-world production traffic with high availability, fault tolerance, and security.

---

## 🏗 Architecture Overview

![Architecture Diagram](architecture/Architecture-diagram.jpeg)


*Services Used:*
- Amazon VPC
- Public & Private Subnets
- Internet Gateway & NAT Gateway
- Application Load Balancer (ALB)
- Auto Scaling Group (ASG)
- EC2 Instances
- CloudFront (CDN)
- Security Groups
- IAM

---

## 🔹 Architecture Flow
1. User accesses the application via *CloudFront*
2. CloudFront forwards requests to *Application Load Balancer*
3. ALB distributes traffic across *EC2 instances*
4. EC2 instances run inside *private subnets*
5. *NAT Gateway* allows outbound internet access securely
6. *Auto Scaling Group* automatically scales instances based on demand

---

## 📊 Key Features
- High Availability across multiple Availability Zones
- Automatic scaling of EC2 instances
- Secure network using private subnets
- Improved global performance using CloudFront
- Cost-optimized and production-ready design

---

## 🧪 Health Checks
- ALB continuously monitors EC2 health
- Unhealthy instances are replaced automatically

---

## 🧹 Cleanup
All AWS resources were deleted after project completion to avoid unnecessary billing.

---

## 📸 Screenshots
Screenshots of all major components are available in the screenshots/ directory.

---

## 🚀 Real-World Use Case
This architecture is widely used for:
- Web applications
- E-commerce platforms
- Company websites
- APIs and microservices

---

## 🧠 Skills Demonstrated
- AWS Networking (VPC, Subnets, NAT)
- Load Balancing & Auto Scaling
- CloudFront CDN
- Infrastructure security best practices
- Cost awareness and cleanup

---

##### Note on Infrastructure Screenshots

The VPC, private subnets, and NAT Gateway were created and validated during the project.
All resources were intentionally deleted after validation to avoid unnecessary AWS charges.

Architecture diagrams and configuration steps accurately reflect the implemented setup.

---
## Author
*Nidhi Kumari*
