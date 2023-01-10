# vpc-module

This repository consists of a terraform module to do the following activities

1.  Creation of VPC in the provided CIDR block.
2.  Create internet gateway for the public subnets and attach with vpc
3.  Creation of Public subnets, one for each availability zone in the region
4.  Creation of Private subnets, one for each availability zone in the region
5.  Creation of Elastic IP for NAT Gateway
6.  Creation of route for public access via the Internet gateway for the vpc
7.  Creation of Private Route Table with route for public access via the NAT gateway
8.  Creation of Private Route for public access via the NAT gateway
9.  Association of Public route table with public subnets.
10.  Association of Private route table with private subnets.

**[Complete documentation of this module can be found here:](https://github.com/pratheeshsatheeshkumar/Reusable-Infrastructure-with-Terraform-Modules-Learn-How-to-Leverage-AWS.#readme)** 
