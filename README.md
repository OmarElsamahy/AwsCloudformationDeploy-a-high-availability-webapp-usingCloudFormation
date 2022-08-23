# AwsCloudformationDeploy-a-high-availability-webapp-usingCloudFormation

This is a Project For deploying a high availability Web Application using Cloudformation 

This template creates Vpc With 2 AZs each each AZ has a Public and private subnet 
each private subnet has at least two Private instances with total of at least 4 instances
These Instances have Auto scaling and Load Balancer for higher availability and Horizontal Scaling up to 6 Instances

InternetGateway For public subnets for Load balancer to be connected to and also have Natgateways that contain an Elastic IP address

Bastion Machine for SSH into Servers to deploy app or alter any information

![Blank document (1)](https://user-images.githubusercontent.com/67503556/186165653-de267ca3-8050-40de-868c-1e9869dc0395.png)
