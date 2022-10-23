## Create network nginx-proxy
docker network create nginx-proxy

## Create nginx-proxy
sudo docker compose -f nginx-proxy.yml create

sudo docker compose -f nginx-proxy.yml start

## Create wordpress instances
sudo docker compose -f wordpress.yml create

sudo docker compose -f wordpress.yml start

