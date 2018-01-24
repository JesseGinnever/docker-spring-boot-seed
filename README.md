# Docker Spring Boot Seed

This is a project seed for Spring Boot java applications running inside of a Docker container

## Getting The Project

Pull the project using git

```
git clone https://github.com/JesseGinnever/docker-spring-boot-seed.git
```

### Starting Server

A step by step series of examples that tell you have to get a development env running

Navigate to the root directory

```
cd docker-spring-boot
```

Build Docker container from openJDK image

```
docker build -f Dockerfile -t docker-spring-boot .
```

Confirm Docker image creation

```
docker images
```

Run Docker container

```
docker run -p 8085:8085 docker-spring-boot
```

Run Docker container

```
docker run -p 8085:8085 docker-spring-boot
```

### Stopping Server

Find running containers

```
dev\docker-spring-boot-seed\docker-spring-boot>docker ps -s
CONTAINER ID        IMAGE                COMMAND                  CREATED              STATUS              PORTS                    NAMES               SIZE
260ab0830d70        docker-spring-boot   "java -jar docker-sp…"   About a minute ago   Up About a minute   0.0.0.0:8085->8085/tcp   hardcore_bardeen    32.8kB (virtual 75
2MB)

```

Stop container by name

```
docker stop hardcore_bardeen

```
