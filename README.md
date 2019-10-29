# VEFT514-SmallAssignment5

### Til að nota docker-compose fileinn

docker-compose up

### Annað

To remove all stopped containers, all dangling images, and all unused networks:
docker system prune

Stop all running containers
docker container stop \$(docker container ls -aq)

Remove all running containers
docker container rm \$(docker container ls -aq)

### Einhverjar skipanir

cd api-gateway/
docker build -t veft/api-gateway .
docker images
cd ..
cd customer-service
docker build -t veft/customer-service .
docker imagesdoc
cd ..
docker network create flamingo-network
docker network ls
docker run -d --name customer-db --network flamingo-network postgres
docker ps
docker run -d --name api-gateway --network flamingo-network veft/api-gateway
docker ps
