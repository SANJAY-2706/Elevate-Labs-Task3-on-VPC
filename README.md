# Elevate-Labs-Task3-on-VPC
# Steps Performed
1.Created a VPC with IPv4 CIDR Block: 10.0.0.0/16
2.Created a  public and Private subnet with 10.0.1.0/24 and 10.0.2.0/24
3.Created and Attached Internet Gateway because it Enables internet access to public Subnet
4.Configered the Route tables and Added the route 0.0.0.0/0 - IGW for Public subnet and 10.0.0.0/16 - local for Private subnet
5.Launched EC2 instance with public and Private subnets and able to ping google.com from public subnet and not able to connect to the instance launched from Private subnet ( Because it is isolated)
