# Linux Server Configuration Project
# Project 6: Linux Server Configuration
# by Mohannad M Nada

# Resources used
* [DigitalOcean] (https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps)
* [Access Remote Server and edit files] (https://www.youtube.com/watch?v=HcwK8IWc-a8)
* As explained by udacity lectures

# IP Address
3.120.39.185

# Port
22 (2200 TCP enabled)

# URL
http://ec2-3-120-39-185.eu-central-1.compute.amazonaws.com/


# Installed software
* Flask, apache2, pip, and the item catalog project dependencies.
* grader user created and added to sudoers as demanded.
* ufw enabled ports 2200, 80 and 123.

# Summary of configurations made
* root access disabled
* grader can undergo sudo commands
* apache2 configured and app served as wsgi app.
* ports configured by ufw 2200 & 80 as tcp while 123 was configured as udp.
* database server is configured to serve data (postgresql db was created with username: catalog and password: catalog)
* catalog.conf file added to sites-available directory
* catalg.wsgi file in /var/www/catalog
* grader sudo password: grader
