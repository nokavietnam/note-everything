
docker ps
docker ps -a

docker -d -p 6000:6370 --name redit-test resdis:latest

docker exec -it redis-test bash 

docker images 

## Network
docker network ls

docker network create mongo-network

docker run -p 27017:27017 -d --network mongodb-network --name mongodb-test -e MONGO_INITDB_ROOT_UERNAME=admin -e MONGODB_INITDB_ROOT_PASSWORD=password mongodb


docker-compose -f mongo.yml up 


==> create file Dockerfile
FROM node:13-alpine
ENV MONGD_DB_USERNAME=admin MONGO_DB_PWD=password

RUN mkdir  -p /home/app
COPY . /home/app
CMD ["node", "server.js" ]


docker build -t my-app:1.0 .


view log container 

docker logs {id_container}

docker exec -it {id_container}  /bin/bash 