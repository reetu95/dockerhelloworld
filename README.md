# Docker Hello World

This project demonstrates a simple "Hello World" application using Docker. The application runs a basic python script inside a docker container. This project servers as an exercise to learn how to create and use DockerFiles.

### Prerequisites
Docker

#### Step 1 : Clone the respository
git clone https://github.com/reetu95/dockerhelloworld.git
cd dockerhelloworld

#### Step 2 : Build the docker image
docker build -t hello-world .

#### Step 3 : Run the docker container
docker run hello-world

#### Step 4 : Clean up
List all containers : 
docker ps -a

Remove specific container : 
docker rm <container_id>

Remove docker image : 
docker rmi hello-world


# Learning Points:
In this projet, I learnt the following :
1) How to create a docker file for simple python application
2) The process of building a docker image using the "docker build" command
3) How to run a docker container with the "docker run" command
4) Basic docker commands for managing conatiners and images
