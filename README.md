# Terraform-AWS-Templates
Terraform AWS Templates


# This template will lunch the following AWS Resources:

#1-VPC
#2-Internet Gateway
#3-Custom Route Table
#4-Public Subnet
#5-Private Subnet
#6-Security group allowing (SSH, HTTP and HTTPS) 
#7-Public Interface
#8-Private Interface
#9-Elastic IP
#10-EC2 Instance - Based on the Latest Amazon Linux AMI- T3.Micro 30GB EBS 
#11-User Data setup to install the following dependencies:
   *YUM Update
   *Curl
   *Latest version of Node.js
   *Latest version of Nginx
   
   *** Make sure to create your own ssh key before hand and reference on your own code like this:
   
   key_name          = "My-Key"
 
   
