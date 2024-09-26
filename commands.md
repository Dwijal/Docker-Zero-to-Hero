# Docker Commands

Some of the most commonly used docker commands are 

#### - docker pull [image-name]:[version]

To pull the image from repo.

#### - docker run [image-name]:[version]

To pull the image and start the container

#### - docker run --name [container-name] -p [localhost]:[container] [image-name][version]

To give name to the container and to do port mapping to the container

#### - docker run -d 

To run the container in detached mode and it runs container in background and print container ID

use `docker run --help` to look into more arguments.

#### - docker build -t my-app:1.0 filelocation

To build the docker image from docker file and tag it 

#### - docker images

Lists docker images on the host machine.

#### - docker ps

Lists running containers on the host machine.

#### - docker ps -a

Lists all inactive running containers on the host machine.

#### - docker stop [container-id/name]

Stops running container.

#### - docker start [container-id/name]

Starts a stopped container.

#### - docker rm [container-id/name]

Removes a stopped container.

#### - docker rmi [imageid/name]

Removes an image from the host machine.

#### - docker pull [imageid/name]
 
Downloads an image from the configured registry.

#### - docker push [imageid/name]

Uploads an image to the configured registry.

#### - docker logs [container-id]

#### - docker inspect [container-id]

It gives all the information regarding the container.

#### - docker exec <container-id> ls /give pathname

To run the command inside docker container

#### - docker exec -it <container-id>  /bin/bash

-it means interactive mode and /bin/bash means opening in bash terminal.


