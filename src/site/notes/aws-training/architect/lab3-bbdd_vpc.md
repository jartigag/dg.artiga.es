# Lab 3: Creating a Database Layer in Your Amazon VPC Infrastructure

The lab environment provides you with the following resources to get started:
an Amazon Virtual Private Cloud (Amazon VPC),
underlying necessary network structure,
3 security groups to control inbound and outbound traffic,
2 EC2 instances in a private subnet,
and an associated EC2 instance profile.

The instance profile contains the permissions necessary to allow the AWS Systems Manager Session Manager feature to access the EC2 instance. 
The following diagram shows the expected architecture of the important lab resources you build and how they should be connected at the end of the lab. 

![](https://github.com/user-attachments/assets/bb7fb3bc-ceab-4e74-9c10-e7f65d3e55d6)

## Task 1: Create an Amazon VPC in a Region
## Task 2: Create public subnets and private subnets
## Task 3: Create an internet gateway
## Task 4: Route internet traffic in the public subnet to the internet gateway
## Task 5: Create a public security group
## Task 6: Launch an Amazon EC2 instance into a public subnet
## Task 7: Connect to a public instance through HTTP
## Task 8: Connect to the Amazon EC2 instance in the public subnet through Session Manager
## Task 9: Create a NAT gateway and configuring routing in the private subnet
## Task 10: Create a security group for private resources
## Task 11: Launch an Amazon EC2 instance into a private subnet
## Task 12: Connect to the Amazon EC2 instance in the private subnet
## (Optional) Task 1: Troubleshooting connectivity between the private instance and the public instance
## (Optional) Task 2: Retrieving instance metadata
