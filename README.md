# install-apache2-setting-mikrotik
Update the package index: Run sudo apt update to update the package manager. 
 
Install Apache2: Run sudo apt install apache2 to install Apache2. When prompted to confirm, type y and press Enter. 
 
Adjust the firewall settings: Run sudo ufw allow 'Apache' to allow traffic on port 80. 
 
Check the web server: Run sudo systemctl status apache2 to check the status of Apache2. 
 
You can also start the Apache service with sudo systemctl start apache2. To enable Apache to run at system startup, you can use a different command. 
 
Apache2 is the current release of the Apache HTTP Server, which is a web server that's commonly used on Linux systems. It's often used as part of the LAMP configuration. 
 
