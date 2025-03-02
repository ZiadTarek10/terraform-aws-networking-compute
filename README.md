# terraform-aws-networking-compute
Terraform project to provision AWS networking and compute resources. It sets up a VPC with public/private subnets, route tables, and an Internet Gateway. Security groups restrict access, allowing SSH/public traffic as needed. A bastion EC2 runs in the public subnet, while an application EC2 is isolated in the private subnet. 
