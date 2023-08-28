Deployment of an Apache Webserver on Linux Instance and hosted a simple HTML based web application.

Source Code

Deployment.
Customize the application dependencies mentioned below on AWS EC2 instance.


Created a Cloudformation Template to deploy a stack containing an EC2 Apache web server with Security Group allowing port 22 and port 80, Built a new VPC with a private and public subnet, Create an Internet Gateway for the VPC.
Created a Private Subnet Route Table and associate it with the Private Subnet.
Created a Public Subnet Route Table and associate it with the Public Subnet.
Created a NAT Gateway in Public Subnet
Updated the Private Subnet Route Table to route the default traffic to NAT for outbound internet connection.
Updated the Public Subnet Route Table to route the default traffic to the Internet Gateway for outbound internet connection.
Installed Apache Web Server on EC2 and deployed the source code into web server document root folder – /var/www/html,
Installed Git,
Published the website on the Web server.
Output the Public IP of the EC2 instance to the CloudFormation Output section.

