This repo contains the Terraform configuration files & code I used to build and deploy a highly-available 2-tier architecture with a web and database tier in AWS.

I used Terraform cloud as a backend management tool for the IaC deployment in addition to the Terraform CLI.

Resources in the infrastructure include: 
    VPC
    Public Subnets 
    Private Subnets
    Internet Gateway
    Elastic IP
    NAT Gateway
    Public Route Table
    Private Route Table
    Route table associations for both the public and private subnets
    Web tier / EC2 instance security group
    EC2 instances with user data script to install a web server (Apache in this case)
    RDS instance Security Group
    Subnet Group for RDS instance
    RDS instance

Link to the project documentation: https://medium.com/@nifemi.sofowoke/deploying-a-2-tier-architecture-with-terraform-f7af2111867a
