# Docker Learn Env

Learning the main features of Docker. Bellow I've listed some commands from running.

## Basic Command Start Container with Ngnix listend Port 8080

```
docker container run -p 8080:80 -v $(pwd)/not-found:/usr/share/nginx/html nginx

```
