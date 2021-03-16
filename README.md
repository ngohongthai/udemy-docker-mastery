### Basic

<br>

> **Start new container from an image** 
> 1. Download image 'iginx' from docker hub
> 2. Started a new container from that image
> 3. Opened port 80 on the host IP
> 4. Routers that traffic to the container IP, port 80
> 5. `webhost` is the name of this container

`docker container run --publish 80:80 --name webhost nginx`

<br>

> **Run docker in the background, using `--detach`**
> 

`docker container run --publish 80:80 --detach --name webhost nginx ` <br>
`docker container run --name mongo -d mongo`

<br>

> **List container**
> 
`docker container ls` <br>
`docker container ls -a` : include exited container.

<br>

> **Stop Container**
> 
`docker container stop <container ID>` <br>
`docker container stop <container Name>`

<br>


> **Show docker logs**
> 
`docker container logs <container Name>` <br>
`docker container logs webhost`

<br>

> **Remove container**
> 
`docker container rm <container ID> <container ID>...`

<br>


### Docker Image


