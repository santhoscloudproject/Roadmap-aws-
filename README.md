# AWS EC2 Static Website Deployment

## Description
This project demonstrates how to deploy a static website on an AWS EC2 Ubuntu instance using Nginx.

## Live Project
EC2 Public IP: http://<YOUR-EC2-PUBLIC-IP>

Example:
http://54.xx.xx.xx

## GitHub Repository
https://github.com/santhoscloudproject/Roadmap-aws-

## Technologies Used
- AWS EC2
- Ubuntu 24.04
- Nginx
- HTML

## How to Run

1. Launch an Ubuntu EC2 instance.
2. Update the instance:
   ```bash
   sudo apt update
   sudo apt upgrade -y
   ```
3. Install Nginx:
   ```bash
   sudo apt install nginx -y
   ```
4. Copy the `index.html` file to:
   ```bash
   /var/www/html/
   ```
5. Open the EC2 Public IP in a browser.

## Screenshot

(Add your screenshot here)
