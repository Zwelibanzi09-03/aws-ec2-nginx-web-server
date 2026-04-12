# AWS EC2 Nginx Web Server Deployment

## Overview

This project demonstrates how to deploy a web server on AWS EC2 using Ubuntu and Nginx.

A static website was hosted on an EC2 instance, configured through SSH, served with Nginx, and made publicly accessible through the instance public IP.

## Project Goal

- Launch an Ubuntu EC2 instance
- Configure secure SSH access
- Install and configure Nginx
- Deploy website files to the server
- Make the website publicly accessible over HTTP

## Tech Stack

- AWS EC2
- Ubuntu Linux
- Nginx
- SSH
- SCP
- Windows PowerShell
- HTML
- CSS
- JavaScript

## Deployment Workflow

- Launched an Ubuntu EC2 instance on AWS
- Configured network access for SSH and HTTP
- Connected securely to the server using SSH
- Installed and started Nginx
- Removed the default Nginx landing page
- Uploaded website files from a local machine using SCP
- Verified file placement and web server status
- Tested the deployed website using the EC2 public IP

## Commands Used

Detailed setup commands are available here:

[View setup commands](./commands/setup.md)

## Screenshots

### EC2 Console / Instance Setup
![EC2 Console / Instance Setup](./screenshots/Screenshot%202026-04-13%20011802.png)

### SSH Connection to Ubuntu Server
![SSH Connection to Ubuntu Server](./screenshots/Screenshot%202026-04-13%20011905.png)

### Nginx Installation / Configuration
![Nginx Installation / Configuration](./screenshots/Screenshot%202026-04-12%20012004.png)

### Nginx Status
![Nginx Status](./screenshots/Screenshot%202026-04-13%20012115.png)

### Website Files on Server
![Website Files on Server](./screenshots/Screenshot%202026-04-13%20012215.png)

### SCP File Upload
![SCP File Upload](./screenshots/Screenshot%202026-04-13%20012310.png)

### Live Website in Browser
![Live Website in Browser](./screenshots/Screenshot%202026-04-13%20012400.png)

### Final Verification
![Final Verification](./screenshots/Screenshot%202026-04-13%20012455.png)

## Outcome

The website was successfully deployed on an AWS EC2 Ubuntu instance and served through Nginx. The deployment was verified through terminal checks, file validation, and browser testing using the public IP address.

## What I Learned

- How to launch and configure an EC2 instance
- How to connect to a Linux server using SSH
- How to install and manage Nginx on Ubuntu
- How to upload files to a remote server using SCP
- How to verify deployment and troubleshoot hosting issues

## Author

Ndandise Xalisa
