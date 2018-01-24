# Docker Spring Boot Seed

This is a project seed for Spring Boot java applications running inside of a Docker container

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
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

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc

