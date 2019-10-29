# VEFT514-SmallAssignment5

### Til að nota docker-compose fileinn

docker-compose up

### Annað

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
