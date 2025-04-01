# Docker_Commands
Do you want to learn Docker commands?

docker run hello-world

docker run -it ubuntu

docker run -it ubuntu bash

docker run -it ubuntu /bin/bash

docker run -it ubuntu /bin/sh

docker ps -a  // to see all the containers

docker ps // to see the running containers

docker start <container_id> // to start the container

docker stop <container_id> // to stop the container

docker rm <container_id> // to remove the container

docker rmi <image_id> // to remove the image

docker images // to see the images

docker build -t <image_name> . // to build the image


docker build -t <image_name> -f <Dockerfile_name> . // to build the image with a specific Dockerfile

docker build -t <image_name> -f <Dockerfile_name> --no-cache . // to build the image with a specific Dockerfile and no cache

docker build -t <image_name> -f <Dockerfile_name> --build-arg <arg_name>=<arg_value> . // to build the image with a specific Dockerfile and build arguments

docker build -t <image_name> -f <Dockerfile_name> --build-arg <arg_name>=<arg_value> --no-cache . // to build the image with a specific Dockerfile, build arguments and no 
cache    // to build the image with a specific Dockerfile, build arguments and no cache  // to build the image with a specific Dockerfile, build arguments and no cache
