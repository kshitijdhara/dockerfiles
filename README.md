# Dockerfiles

The follow repository contain various docker files to run and create Docker container readily 
if Dockerfile then name the file Dockerfile 
if docker compose file type then name the file docker compose.yml

# Prerequistes
Docker

Docker-compose

## Download Docker Destop for Windows and Mac
https://www.docker.com/products/docker-desktop

## Download Docker for Linux
sudo apt-get install docker.io

# Dockerfile.yml extensions
To create an image using Dockerfile cd into the folder containing the Dockerfile and run
## docker build .
or
## docker build -t tagname . 

# docker compose.yml
to create and run an image using docker compose.yml cd into the folder containing the docker compose.yml file and run
## docker-compose up
this creates a container running the specified instructions.
## docker compose down 
this exit and stops the container 
