
From your Docker host, run the following command to pull down and enter an interactive shell on the provided development container.

```
# It may take some time to complete this command while the full container is downloaded
docker run -it --name botlab -v /var/run/docker.sock:/var/run/docker.sock hpreston/devbox:latest

[root@cf95a414877e coding]#

```

