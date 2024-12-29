# AWS Three Tier Web Architecture Project

## Description
This workshop provides a hands-on experience building a three-tier web architecture in AWS. Participants will manually create and configure network, security, application, and database components to establish a highly available and scalable architecture.

## Audience
This introductory-level workshop is designed for technical professionals with foundational AWS knowledge of:
- Amazon VPC
- Amazon EC2
- Amazon RDS
- Amazon S3
- Elastic Load Balancing
- AWS Console navigation

## Pre-requisites
1. Active AWS Account
   - New users can create an account at [AWS Console](https://aws.amazon.com/)
2. IDE or text editor
3. Basic understanding of web applications
4. Familiarity with networking concepts

# AWS Three-Tier Web Architecture

A scalable, reliable, and secure cloud architecture that separates an application into three logical layers: presentation tier, application tier, and data tier.

## Architecture Overview
The architecture consists of three primary tiers:

### Presentation Tier
- Front-end layer handling user interactions
- Hosted in public subnets
- Protected by security groups
- Served through Application Load Balancer

### Application Tier
- Business logic layer processing user requests
- Deployed in private subnets
- Auto-scaled EC2 instances
- Secure communication with data tier

### Data Tier
- Backend layer for data storage and management
- Amazon Aurora for reliable database operations
- Private subnet deployment
- Encrypted data at rest

## AWS Services Utilized
- EC2 (Elastic Compute Cloud)
- Amazon Aurora
- Amazon S3
- VPC (Virtual Private Cloud)
- Subnets (Public & Private)
- Route Tables
- NAT Gateway
- Security Groups
- Elastic Load Balancing
- IAM (Identity and Access Management)

## Architecture Highlights
- VPC setup with public and private subnets across multiple Availability Zones
- NAT Gateways for secure outbound internet access from private subnets
- Application Load Balancer (ALB) for efficient traffic distribution
- Amazon RDS for database management
- Auto Scaling Groups (ASG) for dynamic EC2 instance management
- AWS Well-Architected Framework compliance

## Implementation Steps
1. VPC and Network Configuration
   - Create VPC with appropriate CIDR block
   - Set up public and private subnets
   - Configure route tables and internet gateway

2. Security Setup
   - Create security groups for each tier
   - Configure IAM roles and policies
   - Set up network ACLs

3. Application Deployment
   - Launch EC2 instances
   - Configure Auto Scaling Groups
   - Set up Application Load Balancer

4. Database Configuration
   - Deploy Amazon Aurora instance
   - Configure backup and recovery
   - Set up encryption

## Accessing the Application
1. Obtain the public IP from the web-instance
2. Open your web browser
3. Enter the public IP address

## Key Features
- High Availability across multiple AZs
- Auto-scaling capabilities
- Secure data transmission
- Fault tolerance
- Cost-effective resource utilization

## Benefits
- Enhanced security through layered architecture
- Improved scalability and performance
- Better maintenance and updates
- Flexible development environment
- Robust disaster recovery

## Best Practices
- Regular security patches and updates
- Monitoring and logging implementation
- Backup and recovery procedures
- Cost optimization strategies
- Performance optimization

## Conclusion
This Three-tier architecture provides a robust foundation for enterprise applications with:
- Scalability
- High availability
- Fault tolerance
- Enhanced security
- Optimal resource utilization

The architecture successfully demonstrates the implementation of AWS best practices and serves as a template for similar enterprise-grade applications.


## Contributing
See [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines on how to contribute to this workshop.

## License
This project is licensed under the MIT-0 License. See the [LICENSE](./LICENSE) file for details.

## Additional Resources
- AWS Documentation

 "C:\Users\reddy\Downloads\AWS Three-Tier Web Architecture.pdf"

- Architecture diagrams

![image](https://github.com/user-attachments/assets/c42bccb8-47c2-4f4b-92d8-a3a0ec48d631)


Steps for implementation processes:-

![image](https://github.com/user-attachments/assets/7f904e20-439b-4b59-a5ed-413e0c019017)

![image](https://github.com/user-attachments/assets/ec4d67be-3c92-407f-8a10-f9ee9fc19381)

![image](https://github.com/user-attachments/assets/a6d94a73-0344-45e9-a0b1-a3c08dbeb184)

![image](https://github.com/user-attachments/assets/a0f465f0-2612-458e-be5f-b6f20fc88984)





