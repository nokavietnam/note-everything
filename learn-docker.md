
docker ps
docker ps -a

docker -d -p 6000:6370 --name redit-test resdis:latest

docker exec -it redis-test bash 

docker images 

