## About
Create nginx proxy container with LetsEncrypt companion.
Only two containers will be created with this file.
New containers will automatically support SSL, no need to configure individually.

## Create network nginx-proxy
docker network create nginx-proxy

## Create image
sudo docker compose up -d

## Create new user
adduser username
usermod -aG sudo username
id username
su - username
sudo ls -l /etc/shadow

## Install Docker
https://docs.docker.com/engine/install/ubuntu/

