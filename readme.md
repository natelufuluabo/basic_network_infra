# Basic Network Config

This is a basic network configuration for deployments on AWS

This configuration creates:

- 1 VPC
- An Internet Gateway attached to the VPC
- A public route table attached to the internet gateway
- 2 public subnets - in differents AZs - associated witht the public route table
- 2 private subnets - in differents AZs

Note: This network configuration is best suited for deployments that will be using EC2