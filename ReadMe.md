## Docker commands

### Check the installation
```sh
docker
```

### Build the image
```sh
docker build -t <image-name> .
```

### See docker images
```sh
docker images
```

### Run the container
```sh
docker run -d -p <host-port>:<container-port> --name <container-name> <image-name>
```

### List the containers
```sh
docker ps
```

### Tag the image
```sh
docker tag <image-name> <docker-id>/<image-name>
```

### Push the image
```sh
docker push <docker-id>/<image-name>
```

### Pull the image
```sh
docker pull <docker-id>/<image-name>
```

### Stop the container
```sh
docker stop <container-name>
```

### Remove the container
```sh
docker rm <container-name>
```

### Remove the image
```sh
docker rmi <image-name>
```
