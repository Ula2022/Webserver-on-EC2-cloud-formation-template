Deployment of an Apache Webserver on Linux Instance and hosted a simple HTML based web application.

Source Code

Deployment.
Customize the application dependencies mentioned below on AWS EC2 instance.


Created a Cloudformation Template using github to automate the deployment a stack containing an EC2 Apache web server with Security Group allowing port 22 and port 80.
Installed Apache Web Server on EC2 and deployed the source code into web server document root folder – /var/www/html,
Installed Git,
Published the website on the Web server.
Output the Public IP of the EC2 instance to the CloudFormation Output section.

