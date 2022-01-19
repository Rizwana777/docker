# docker
Basics of docker

* This command will add tag to our image
  - docker build -t rizwana/redis .

* Normally we can build docker image as
  - docker build .

* Once docker is build we can run our custom image
  - docker run rizwana/redis

* Enter inside container using
  - docker run -it alpine sh

* Get list of docker containers which are running
  - docker ps

* Get list of all running and stopped containers
  - docker ps --all

* use below command to see what is happening in container
  - docker kill <container-id>