# EC2 Nginx Setup Commands

These are the exact commands I used while setting up and deploying the website on the EC2 Ubuntu server.

---

## Connecting to the server

ssh -i ec2-key.pem ubuntu@your-public-ip

---

## Preparing the server

sudo apt update  
sudo apt install nginx -y  

sudo systemctl start nginx  
sudo systemctl enable nginx  

sudo systemctl status nginx  

---

## Basic navigation

pwd  
ls  

---

## Uploading project files from Windows (PowerShell)

scp -i "C:\Users\linda\Downloads\ndandise-key.pem" -r . ubuntu@16.28.54.248:~  

---

## Moving files into the web server directory

sudo mv index.html /var/www/html/  
sudo mv style.css /var/www/html/  
sudo mv script.js /var/www/html/  
sudo mv media /var/www/html/  

---

## Checking files on the server

ls /var/www/html  
ls /var/www/html/media  

---

## Debugging image issues

grep -r "image1" /var/www/html  

ls -ld /var/www/html  
ls -ld /var/www/html/media  

sudo chmod 755 /var/www/html/media  
sudo chmod 644 /var/www/html/media/*  

---

## Final steps

sudo systemctl restart nginx  

exit
