# What is it
This is a docker support for the Altiore project.

It dockrizes two services such as:
* PostgreSQL 10.6
* Redis 5.0

# What is it for
It helps you to deploy the project on any environment in seconds, keeping the exact versions of software. Also, all additions will be automatically installed as well as all predefined data you want to initially have.

# How to use it
## Preparation
First, place all of the files keeping structure into the root of your project.

## Usage
### How to run containers
Use the following command to pull, build and run containers.
```
$ docker-compose up -d
```

This command step by step download all needed images, build them and run. In other words, it is the same as if you run the following commands one by one:
```
$ docker-compose pull
$ docker-compose build
$ docker-compose up
```

### How to check the current status
 To check the status, perform:
```
$ docker-compose ps
```
