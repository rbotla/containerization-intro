# Docker CLI Commands

> Build image
```
docker build -t node-web-app .
```

> Check if image creation was successful
```
docker images
```

> Run the image
```
docker run -p 3000:8080 -d node-web-app
```

> Check if the container is running
```
docker ps
```

> Enter the container
```
docker exec -it <container id> /bin/bash
```

> Check if the server is running
```
curl -i localhost:3000
```