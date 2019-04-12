# Steps

## Build the Image
```
docker build -t <your username>/node-web-app .

docker images
```

## Run the Image
```
docker run -p 49160:8080 -d <your username>/node-web-app

docker ps
```

## Extra Commands
* Kill the container
```
docker kill <container name>
```

* Delete unused images
```
docker system prune -a
```
