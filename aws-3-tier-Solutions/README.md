# AWS 3 Tier Architecture Solution

<p align="center">
  <img src="3tierarchitecture.gif"/>
</p>

## Description

As part of my project portfolio, I have designed and implemented an AWS architecture for a three-tier application using a variety of AWS services, including Amazon Elastic Compute Cloud (EC2), Amazon Relational Database Service (RDS), Amazon Virtual Private Cloud (VPC), Application Load Balancer (ALB), Classic Load Balancer (CLB), Network Load Balancer (NLB), Autoscaling, Amazon Route53, AWS Certificate Manager (ACM), Amazon CloudWatch, Amazon Simple Notification Service (SNS), AWS CodePipeline, AWS CodeBuild, Amazon Simple Storage Service (S3), and more.

The architecture utilizes EC2 for scalable compute resources, RDS for managed database services, and VPC for networking isolation and security. The load balancing is managed by ALB, CLB, and NLB, which distribute traffic among the EC2 instances based on the application requirements. Autoscaling is utilized to automatically adjust the EC2 instances in response to changes in the demand for the application.

Route53 provides DNS management and routing, while ACM is utilized for SSL/TLS certificate management, ensuring secure communication between the application and the end-users. CloudWatch provides comprehensive monitoring and logging services, enabling proactive management of the application.

SNS is utilized for notifications and alerts, providing timely information to the stakeholders in the event of any issues. For continuous integration and continuous deployment (CI/CD), AWS CodePipeline and AWS CodeBuild are utilized. CodePipeline provides a fully managed CI/CD service, while CodeBuild is used for building and testing the application.

Finally, S3 is utilized for storage of static files and artifacts, providing a cost-effective and scalable storage solution for the application.

Overall, this AWS architecture provides a highly available, scalable, and secure environment for the three-tier application.

### 1. AWS VPC Architecture Structure 01

<p align="center">
  <img src="/aws-3-tier-Solutions/jpg-format\AWS VPC Structure.jpg"/>
</p>

### 2. AWS VPC Architecture Structure 02

<p align="center">
  <img src="/aws-3-tier-Solutions/jpg-format\AWS VPC-SG.jpg"/>
</p>

### 3. AWS VPC Architecture. EC2 Instaces and SG

<p align="center">
  <img src="/aws-3-tier-Solutions/jpg-format\AWS VPC-EC2.jpg"/>
</p>

### 4. AWS 3-Tier Architecture. EC2 and Classic Load Balancer

<p align="center">
  <img src="/aws-3-tier-Solutions/jpg-format\AWS VPC-EC2 CLB.jpg"/>
</p>

### 5. AWS 3-Tier Architecture. EC2 and Application Load Balancer

<p align="center">
  <img src="/aws-3-tier-Solutions/jpg-format\AWS VPC-EC2 ALB.jpg"/>
</p>

### 6. AWS 3-Tier Architecture. ALB with AutoScalingGroup

<p align="center">
  <img src="/aws-3-tier-Solutions/jpg-format\AWS VPC-EC2 NLB ASG LT-LC.jpg"/>
</p>

### 7. AWS 3-Tier Architecture. Network Load Balancer and ASG

<p align="center">
  <img src="/aws-3-tier-Solutions/jpg-format\AWS VPC-EC2 NLB ASG LT-LC.jpg"/>
</p>

### 8. AWS 3-Tier Architecture. Network Load Balancer with CloudWatch

<p align="center">
  <img src="/aws-3-tier-Solutions/jpg-format\AWS VPC-EC2 NLB ASG LT-LC CW.jpg"/>
</p>

### 9. AWS 3-Tier Architecture. Context Path Based Routing

<p align="center">
  <img src="/aws-3-tier-Solutions/jpg-format\AWS VPC-EC2 ALB CPBR.jpg"/>
</p>

### 10. AWS 3-Tier Architecture. Context Path Based Routing + RDS

<p align="center">
  <img src="/aws-3-tier-Solutions/jpg-format\AWS VPC-EC2 ALB CPBR RDS.jpg"/>
</p>

### 11. AWS 3-Tier Architecture. Host Header Based Routing

<p align="center">
  <img src="/aws-3-tier-Solutions/jpg-format\AWS VPC-EC2 ALB HHBR.jpg"/>
</p>

### 12. AWS 3-Tier Architecture. Query String and Host Header

<p align="center">
  <img src="/aws-3-tier-Solutions/jpg-format\AWS VPC-EC2 ALB QSHH.jpg"/>
</p>

### 13. AWS 3-Tier Architecture. CICD Pipelines

<p align="center">
  <img src="/aws-3-tier-Solutions/jpg-format\WS VPC-EC2 CICD Pipeline.jpg"/>
</p>
