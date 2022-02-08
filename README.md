# Utorrent Server
Ubuntu 20.04 LTS, Nginx 1.18.0 and Utorrent Server in one Docker Image

##  How to use this image
- Starting this image is simple:
```
docker run -d --name <container_name> -p 8080:80 galanghanaf/ubuntu-utorrentserver:latest
```
- After that, get the container ip with command :
```
docker exec -it <container_name> /bin/bash -c "/sites/utorrent.sh"
```
- And done.
