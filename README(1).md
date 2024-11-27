This repository contains yml file to run MySQL and Wordpress container using Docker Compose.

#To download docker compose :

curl -SL https://github.com/docker/compose/releases/download/v2.30.3/docker-compose-linux-x86_64 -o /usr/local/bin/docker-compose

#Give execute permission to docker-compose file:

chmod +x /usr/local/bin/docker-compose

#To compose:

docker-compose up

#Create wp.yml file and to run container :

docker-compose -f wp.yml up
