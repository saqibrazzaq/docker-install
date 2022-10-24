## Create network nginx-proxy
docker network create nginx-proxy

## Create nginx-proxy
sudo docker compose -f nginx-proxy-ssl.yml create

sudo docker compose -f nginx-proxy-ssl.yml start

sudo docker compose -f nginx-proxy-ssl.yml stop

sudo docker compose -f nginx-proxy-ssl.yml rm

## Create wordpress instances
sudo docker compose -f wordpress.yml create

sudo docker compose -f wordpress.yml start

sudo docker compose -f wordpress.yml stop

sudo docker compose -f wordpress.yml rm

