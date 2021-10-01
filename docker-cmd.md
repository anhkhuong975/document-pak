Tutorial Document:
https://github.com/nnvgm/docker-series/tree/master/p5-basic-command


# access into container
docker exec -it [container id] sh

# delete all container
docker rm $(docker ps -aq)

# image inspect
docker inspect [image]

# image history
docker history [image]

Docker compose
\/ \/ \/ \/ \/

# Checking Logs
docker-compose logs

# Checking progess
docker-compose top

# Stop
docker-compose stop

# Run/up compose
docker-compose up