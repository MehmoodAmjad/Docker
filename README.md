# Docker

# Install Docker

```
https://docs.docker.com/get-docker/
```

# Build Image
```
docker build -t image_name
```
# Run Container
```
docker run -dp 3000:3000 image_name
```
# Docker Compose

Up
```
docker-compose up -d
```
Down
```
docker-compose down
```

# Basic Commands

show the list of containers
```
docker ps
```
stop the container
```
docker stop <container_id>
```
remove the container
```
docker rm <container_id>
```
Push to a repo
```
docker push docker/getting-started
```
