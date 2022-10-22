## Clone repository

First clone the repository

git clone https://github.com/saqibrazzaq/docker-install.git

For updates

git pull origin master

## Run containers

First create the containers

sudo docker compose -f stack.yml create

Then start

sudo docker compose -f stack.yml start

To stop

sudo docker compose -f stack.yml stop

To remove

sudo docker compose -f stack.yml rm
