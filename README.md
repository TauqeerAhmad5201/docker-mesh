# docker-mesh

# Docs
https://docs.docker.com/
https://aws.amazon.com/docker/


Difference b/w virtualization and containerization. 

- In virtualization - hardware will be used from the system and will be fixed for every OS we install through the hypervisor
- In containerisation - hardware will be used from the system but will not be fixed, it will be allocated for the time it is being used. 


Docker uses OS-level containerization. 

## Official 
https://docs.docker.com/get-started/
https://docs.docker.com/get-started/02_our_app/


## Why use Docker?

Docker is so popular today that “Docker” and “containers” are used interchangeably. But the first container-related technologies were available for years—even decades (link resides outside IBM)—before Docker was released to the public in 2013. 



## Cheat Sheet 

- `docker ps`: List all running containers.
- `docker run`: Create a new container and run it.
- `docker stop`: Stop a running container.
- `docker start`: Start a stopped container.
- `docker restart`: Restart a running container.
- `docker rm`: Remove a container.
- `docker images`: List all images
- `docker build`: Build an image from a Dockerfile.
- `docker push`: Push an image to a registry.
- `docker pull`: Pull an image from a registry.
- `docker inspect`: Inspect or visionize all the docker images
- `docker stats`: This command is used to get statistics about a Docker container.
- `docker logs`: This command is used to view the logs for a Docker container.
- `docker commit`: This command creates a new image from an existing container.
- `docker network`: This command creates and manages Docker networks.
- `docker system df`: Displays disk usage information for Docker containers, images, and volumes.
These are just a few of the many mid-level Docker commands.
- `docker system prune:`: Removes unused Docker data, such as dangling images and unused volumes.
- `docker buildx build`: Docker images using a multi-platform builder.
- `docker image inspect:`: Displays detailed information about a Docker image.
- `docker swarm leave:` Leaves a Docker swarm cluster.
- `docker swarm init`: Run docker swarm init to create a single-node swarm on the current node
- `docker volume prune`: Removes unused Docker volumes.
- `docker volume inspect`: Displays detailed information about a Docker volume.
- `docker rm`:
