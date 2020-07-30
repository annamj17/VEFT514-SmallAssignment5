# VEFT514-SmallAssignment5

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
Create a microservice structure with docker containers.
		
## To be able to use the docker-compose file
docker-compose up

## Other
To remove all stopped containers, all dangling images, and all unused networks:

```
docker system prune:
```

Stop all running containers

```
docker container stop \$(docker container ls -aq)
```

Remove all running containers

```
docker container rm \$(docker container ls -aq)
```
