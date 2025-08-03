# AWS EC2 NGINX Hosting Project

This project demonstrates how to launch an AWS EC2 Ubuntu instance, install and configure NGINX, and serve a simple static website.

## Purpose

To learn and practice deploying a web server on a cloud VM using AWS EC2 and NGINX.

## What You’ll Learn

- How to launch an EC2 instance on AWS
- How to SSH into the server securely using SSH key pairs
- How to install and configure NGINX to serve web content
- How to open the website in a browser using the EC2 public IP
- How to manage security groups to allow HTTP traffic

## Project Files

- `default-nginx-config`: Custom NGINX server configuration file
- `index.html`: Sample simple website served by NGINX

## Setup Overview

1. Launch EC2 Ubuntu instance
2. SSH into the instance with your `.pem` key
3. Install NGINX using `sudo apt install nginx`
4. Copy your website files to `/var/www/html`
5. Configure NGINX to serve your content (custom config optional)
6. Open port 80 in AWS security groups
7. Visit your public IP in a browser to see your site

## Notes

- This project can be extended to serve dynamic content or use SSL certificates.
- Always secure your private key and restrict server access.
