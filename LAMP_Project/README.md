### **WEB STACK IMPLEMENTTAION**

## `Documentation That shows how to implement LAMP(LINUX,APACHE,MYSQL,PHP) ON AWS`

`LAMP STACK IMPLEMENTATION IN AWS`: Used to host websites and web apps.

## Installing Apache and Updating the Firewall

Before installing, i needed to authenticate my laptop to have acess to the server running a ubuntu operating system on my AWS Account. 
I used that PEM key to connect to my EC2 instance via ssh

![Alt text](<Images/Screenshot 2023-09-20 at 11.12.56.png>)

`sudo apt update:refreshes your systems package list, helping it know about the latest versions`

![Alt text](<Images/Screenshot 2023-09-20 at 12.39.33.png>)

`sudo apt install apache2`

![Alt text](<Images/Screenshot 2023-09-20 at 12.51.51.png>)

Installing Apache using Ubuntu's package manager 'apt'

To verify that apache2 is runninh as a service in our ubuntu instance, we will use

`sudo systemctl status apache2`

Below is the outcone of  the apache status, which is running amd active 

![Alt text](<Images/Screenshot 2023-09-20 at 12.57.51.png>)

Verify apache2 webpage is accessible from the server

`curl http://localhost`   or `curl http://<public address:80>`

![Alt text](<Images/Screenshot 2023-09-20 at 13.21.33.png>)

![Alt text](<Images/Screenshot 2023-09-20 at 13.24.03.png>)

This means my web server is now correctly installed and accessible through my firewall

### INSTALLING MYSQL

Installing MYSQL on the ubuntu server

`sudo apt install mysql-server`

![Alt text](<Images/Screenshot 2023-09-20 at 14.14.54.png>)

Log into the MYSQL console

`sudo mysql`




