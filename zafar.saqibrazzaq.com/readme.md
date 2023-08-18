## Create network nginx-proxy
docker network create nginx-proxy

## Create nginx-proxy
sudo docker compose -f nginx-proxy.yml create

sudo docker compose -f nginx-proxy.yml start

sudo docker compose -f nginx-proxy.yml stop

sudo docker compose -f nginx-proxy.yml rm

## Create wordpress instances
sudo docker compose up -d

### Manual start, stop, remove
sudo docker compose start

sudo docker compose stop

sudo docker compose rm

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
