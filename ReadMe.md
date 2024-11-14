
# Run following command on terminal

docker build --tag=hellodocker .

docker image ls

docker run -p 4000:80 hellodocker
docker run --detach --publish 4000:80 hellodocker

docker container stop eb59761a785d

docker rm CONTAINER_ID

docker container ls