**Create docker network script**

- docker-network.sh

  docker network create api_net -d bridge --scope local --subnet 172.22.2.0/24 --attachable
--------------------------------------------------------------------------------------------
