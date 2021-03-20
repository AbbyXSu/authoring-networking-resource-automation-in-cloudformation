Desired Architecture
This diagram consists of the following:
![Capture](https://user-images.githubusercontent.com/77119427/111888348-9f617080-89d3-11eb-88bd-5f90aa1f1f45.PNG)

A two-tier VPC with one public subnet and one private subnet
An Internet Gateway in the VPC
An ELB in the public subnet
A Network Address Translation EC2 instance in the public subnet
An EC2 auto-scaling group in the private subnet
A DynamoDB table
IAM role to control access to the DynamoDB table
SecurityGroups for the ELB, auto-scaling group, and NAT instanceDesired Architecture
This diagram consists of the following:

A two-tier VPC with one public subnet and one private subnet
An Internet Gateway in the VPC
An ELB in the public subnet
A Network Address Translation EC2 instance in the public subnet
An EC2 auto-scaling group in the private subnet
A DynamoDB table
IAM role to control access to the DynamoDB table
SecurityGroups for the ELB, auto-scaling group, and NAT instance
