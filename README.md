**Create docker network script**

**_- show docker container_**
docker ps, docker ps -a

**_- show docker images_**
docker images

**_- show docker images all details_**
docker image inspect

**_- show docker network_**
docker network ls

**_- show docker volume_**
docker volume ls

**_- show logs_**
docker logs <container_name>

**_- build image_**
docker build -t <image_name> .












  
**_- docker-network.sh_**

docker network create api_net -d bridge --scope local --subnet 172.22.2.0/24 --attachable

