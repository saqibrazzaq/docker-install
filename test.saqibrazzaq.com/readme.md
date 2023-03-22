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

