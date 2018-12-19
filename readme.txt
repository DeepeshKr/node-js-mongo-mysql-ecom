#start mongo into docker
docker pull mongo

docker run --name mongodb -p 37017:27017 -d mongo

docker ps

To start docker type
docker start mongodb