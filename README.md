# docker-compose-demo
This repo contains sample files for docker-compose

pre requisite
docker and git 

update system

To download and install Compose standalone, run
$ curl -SL https://github.com/docker/compose/releases/download/v2.12.2/docker-compose-linux-x86_64 -o /usr/local/bin/docker-compose

sudo chmod +x /usr/local/bin/docker-compose

Test and execute compose commands using docker-compose.
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose

docker-compose –version

####################################################################
docker compose up

docker-compose up -f docker-compose.yml web

docker-compose images

docker-compose ps

docker-compose up -d

docker-compose down

docker-compose start service_name

docker-compose stop service_name

docker-compose up -d --scale service=5

docker-compose up -f service_name

docker-compose logs -f service_name

docker-compose rm service_name
