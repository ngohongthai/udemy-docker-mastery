### Note
> **Start new container from an image** 
> 1. Download image 'iginx' from docker hub
> 2. Started a new container from that image
> 3. Opened port 80 on the host IP
> 4. Routers that traffic to the container IP, port 80

`docker container run --publish 80:80 nginx `


> **Run docker in the background, using `--detach`**
> 

`docker container run --publish 80:80 --detach nginx `

> **List container**
> 
`docker container ls`

> **Stop Container**
> 
`docker container stop <container ID>`

