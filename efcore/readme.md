## Pre-req
nginx proxy with ssl should be already installed and running

## Create wordpress instances
sudo docker compose up -d

## Upload max file size for divi theme
Open Docker terminal

sudo docker exec -it <name> bash

### Install nano
apt-get update
apt-get upgrade
apt-get install nano

### Create php.ini in public/html folder
nano php.ini
upload_max_filesize = 64M
post_max_size = 128M

### Restart apache on docker
sudo /etc/init.d/apache2 restart

