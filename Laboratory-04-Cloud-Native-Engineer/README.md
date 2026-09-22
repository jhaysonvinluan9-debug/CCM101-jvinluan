Mission Overview

In this laboratory, I learned how to use Docker to deploy and manage a web server using a container. I used Killercoda to run Docker commands and deployed an Nginx web server inside a Docker container.

Objectives

* Understand the basic purpose of containers.
* Verify that Docker is installed and running.
* Download and run an Nginx Docker image.
* Use port mapping to access a web server inside a container.
* Learn how to manage the lifecycle of a Docker container.
* Document the Docker commands and results.

Docker Commands Executed

docker --version
docker info
docker pull nginx
docker run -d -p 8080:80 --name nginx-server nginx
curl http://localhost:8080
docker ps
docker stop nginx-server
docker ps
docker rm nginx-server

Skills Learned

I learned how to check if Docker is installed and running, download an image from Docker Hub, and run an Nginx container. I also learned how to use port mapping to access a web server running inside a container. In addition, I learned how to list, stop, verify, and remove Docker containers.

Challenges Encountered

One challenge I encountered was entering the port mapping correctly when running the Nginx container. I initially received an error because the port format was incorrect. After correcting it to 8080:80, the container started successfully, and I was able to access the Nginx welcome page using the curl command.
