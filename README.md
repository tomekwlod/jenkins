# Jenkins in docker 

Yet another jenkins implementation using docker image (LTS). It is still experimental but fully functional. It contains a docker client inside the container but also connects through the socket to the host docker as well.

<br />

### Install

Simply clone this repo to your machine and run `docker-compose up -d --build`. I assume that you have docker and docker-compose already installed on your host. During the initialization a folder `jenkins_home` will be created and connected to container as a valume. 
Once contener is up and running you have unlock it with the temporary password for the first time (password will be displayed or simply print the container log).

