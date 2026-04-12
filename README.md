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

## Screenshots

### EC2 Instance Launch and Initial Setup
![EC2 Instance Launch and Initial Setup](./screenshots/Instance%20launch%20and%20initial%20setup.png)

### Security Group Configuration
![Security Group Configuration](./screenshots/Security%20group%20configuration.png)

### First Remote Connection to Ubuntu
![First Remote Connection to Ubuntu](./screenshots/First%20remote%20connection%20to%20Ubuntu.png)

### Installing and Managing Nginx
![Installing and Managing Nginx](./screenshots/Installing%20and%20managing%20Nginx.png)

### Deploying Website Files
![Deploying Website Files](./screenshots/Deploying%20the%20website%20files.png)

### Final Live Deployment
![Final Live Deployment](./screenshots/Final%20live%20deployment.png)

### Roles in the Solution
![Roles in the Solution](./screenshots/Roles%20in%20the%20solution.png)

## Outcome

The website was successfully deployed on an AWS EC2 Ubuntu instance and served through Nginx. The deployment was verified through terminal checks, file validation, and browser testing using the public IP address.

## What I Learned

- How to launch and configure an EC2 instance
- How to connect to a Linux server using SSH
- How to install and manage Nginx on Ubuntu
- How to upload files to a remote server using SCP
- How to verify deployment and troubleshoot hosting issues
