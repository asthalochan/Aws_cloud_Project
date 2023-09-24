# Aws_cloud_Project
Highly Available Web Application with Auto Scaling, SSL Encryption, and Remote Database Access


This project demonstrates the setup of a highly available web application on AWS, incorporating various AWS services and best practices. It includes the following components:

- Virtual Private Cloud (VPC) with 4 subnets (2 public, 2 private)
- Internet Gateway, NAT Gateway, and Route Tables
- 2 EC2 instances hosting a sample website
- Application Load Balancer for traffic distribution
- Auto Scaling Group with CloudWatch-based scaling policies
- MySQL RDS Database in a private subnet
- Secure remote access to the database via OpenVPN
- SSL certificate configuration for the demo website
- Route 53 Hosted Zone for DNS management

## Project Overview

This project is designed to provide a step-by-step guide on how to create a robust and highly available web application in the AWS cloud. Below are the main steps involved:

1. **Setting Up the AWS VPC**
   - Creation of a VPC
   - Configuration of 4 subnets (2 public, 2 private)
   - Attachment of Internet Gateway and NAT Gateway
   - Configuration of route tables for routing traffic

2. **Launching EC2 Instances**
   - Launching 2 EC2 instances in the public subnets
   - Configuration of EC2 instances to host a sample website
   - Attachment of an Application Load Balancer

3. **Implementing Auto Scaling**
   - Creation of an Auto Scaling Group
   - Configuration of CloudWatch alarms for automatic scaling based on CPU utilization

4. **Creating an RDS Database**
   - Launching an RDS instance in a private subnet
   - Database configuration including security groups and parameter groups

5. **Securely Accessing the Database**
   - Setting up an OpenVPN server in AWS
   - Connecting to the RDS database securely from a local computer using MySQL Workbench via the OpenVPN server

6. **SSL Certificate and DNS Configuration**
   - Obtaining and configuring an SSL certificate for the demo website
   - Creating a Hosted Zone in Amazon Route 53 for DNS management
   - Setting up listeners in the Load Balancer to enable SSL termination

## Getting Started

For detailed step-by-step instructions and screenshots, please refer to the [Project PDF Guide](project_guide.pdf).

## Additional Resources

- [AWS Documentation](https://aws.amazon.com/documentation/)
- [OpenVPN Documentation](https://openvpn.net/documentation/)
- [MySQL Workbench Documentation](https://dev.mysql.com/doc/workbench/en/)

## Conclusion

This project demonstrates the implementation of a high availability web application architecture on AWS, leveraging the power of VPCs, EC2 instances, Auto Scaling, RDS databases, VPNs, and SSL certificates. It serves as a reference for those looking to deploy similar solutions in the AWS cloud.

For any questions or clarifications, please feel free to open an issue or contact asthalochan at mohantaastha@gmail.com
