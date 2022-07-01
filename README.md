# Docker and Kubernetes
## Docker
### ./ What is Docker
### ./ Install Docker
 - Access this link to download then install Docker:
https://docs.docker.com/engine/install/

 - Verify Installation by command:
```
docker --version
docker ps
```

### ./ Images and Containers
#### Docker Image
 - Image is a template for creating an environment of your Choice
 - Snapshot
 - Has everything need to run your Apps: OS, Software, App

#### Container
 - Running instance of an Image

### ./ Nginx image
 - What is Ingix? Nginx (pronounced "engine-x") is an open source reverse proxy server for HTTP, HTTPS, SMTP, POP3, and IMAP protocols, as well as a load balancer, HTTP cache, and a web server (origin server).

- Pull Nginx image
```
docker pull nginx
```
Refer: https://hub.docker.com/

- Check images
```
docker images
```

### ./ Run containers
 - Run container
```
docker run nginx:latest             // run in terminal
docker run -d nginx:latest          // running in task mode
```

 - List container
```
docker container ls
docker ps
```

 - Cancel running
```
Ctrl + C       // for running in terminal

```

### ./ Expose ports




