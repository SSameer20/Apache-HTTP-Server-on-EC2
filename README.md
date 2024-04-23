# Apache HTTP Server on EC2
The Apache HTTP Server Project is an effort to develop and maintain an open-source HTTP server for modern operating systems including UNIX and Windows. The goal of this project is to provide a secure, efficient and extensible server that provides HTTP services in sync with the current HTTP standards.

## Overview
This project demonstrates how to set up a web server on Amazon EC2 (Elastic Compute Cloud) instance using CentOS. The server is configured to host a website using the Apache HTTP Server (httpd). This README provides step-by-step instructions on how to deploy the web server and host your website on the EC2 instance.

## Prerequisites
Before getting started, ensure you have the following:
- An AWS account with permissions to create and manage EC2 instances.
- Basic knowledge of the Linux command line.
- Git installed on your local machine if you plan to clone a Git repository.

## Deployment Steps
1. **Launch EC2 Instance**: Start by launching an EC2 instance with CentOS as the operating system.
2. **Connect to Instance**: Once the instance is running, SSH into it using a terminal or an SSH client.
3. **Update Packages**: Update the package repository and installed packages using `yum update -y`.
4. **Install Apache**: Install the Apache HTTP Server using `yum install -y httpd`.
5. **Check Status**: Verify the status of Apache using `systemctl status httpd`.
6. **Prepare Website Files**: Create a directory for temporary files and clone your website project using Git.
7. **Move Files**: Move the project files from the t
