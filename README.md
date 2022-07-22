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

# Setting up Apache Ranger and Hadoop Services on Docker

The tutorial on the link below can be followed for setting up containers for running docker and Hadoop Services on Ranger

```
https://medium.com/swlh/hands-on-apache-ranger-docker-poc-with-hadoop-hdfs-hive-presto-814344a03a17
```

# Setting up Hue

The following command automatically sets up the latest hue container on docker
```
docker run -it -p 8888:8888 gethue/hue:latest
```
