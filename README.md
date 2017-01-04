# mongodb-docker

# Docker util commands:
##### docker ps -a -> list containers
##### docker rm <id> -> remove container
##### docker images -> list images
##### docker rmi <id> -> remove image

# How to build the image:

##### docker build -t yourname:imagename path2Dockerfile

# How to run the image:

##### docker run -name containername -p 27017:27017 -v /data/db:/data/db yourname:imagename
