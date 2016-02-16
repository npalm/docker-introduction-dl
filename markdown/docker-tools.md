# Docker tools
![docker-tools](images/docker-tools.jpg)

!SUB
### Docker compose
Compose is a tool for defining and running complex applications with Docker. With Compose, you define a multi-container application in a single file, then spin your application up in a single command which does everything that needs to be done to get it running.

!SUB
### Docker compose
```
gitlabdb:
  image: postgres
  environment:
    - POSTGRES_USER=gitlab
    - POSTGRES_PASSWORD=password
gitlab:
  image: sameersbn/gitlab
  links:
    - gitlabdb:postgresql
  environment:
    - DB_USER=gitlab
    - DB_PASS=password
  ports:
    - "10080:80"
  volumes:
    - ./data/gitlab/data:/home/git/data

```


!SUB
### Docker machine
Machine makes it really easy to create Docker hosts on your computer, on cloud providers and inside your own data center. It creates servers, installs Docker on them, then configures the Docker client to talk to them.
![docker-machine](images/beta.png)

!SUB
### Docker swarm
Docker Swarm is native clustering for Docker. It turns a pool of Docker hosts into a single, virtual host.


!SUB
## TOOLS - TOOLS - TOOLS
![tools](images/tools.jpg)


!SUB
## What about Microsoft?
![tools](images/docker-microsoft.jpg)

!SUB
## Container solution on Azure
![tools](images/docker-windows-linux.jpg)
