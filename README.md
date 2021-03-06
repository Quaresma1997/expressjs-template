# ExpressJS Template

## Product View

Expressjs + Passportjs + JWT + Postgres + Pgadmin + Docker

## Project Architecture Overview

## Setup Project

* [Cloning Project](#cloning-project)
* [Installing Docker and Docker Compose](#installing-docker-and-docker-compose)
* [Configured containers](#configured-containers)


### Cloning Project
```shell
$ git clone https://github.com/diogotorres97/expressjs-template
$ cd expressjs-template
```

### Installing Docker and Docker Compose

Before starting you'll need to have __Docker__ and __Docker Compose__ installed on your PC.
The official instructions are in [Install Docker](https://docs.docker.com/install/) and in [Install Docker Compose](https://docs.docker.com/compose/install/#install-compose).

Note: If you are getting permission error one the docker run hello-world or if you get a warning ".docker/config.json: permission denied run..." follow [this instructions](https://docs.docker.com/install/linux/linux-postinstall/).

### Configured containers

__To start the environment__ :

```shell
$ docker-compose up
```

Access to:
- http://localhost:3000 -> to access the server
- http://localhost:5050 -> to access pgadming to interact with database


### How to run the tests
  ```shell
   $ chmod +x test.sh # set executable permissions
   $ sh test.sh
   ```


### How to run the linter
```shell
$ cd server
$ docker-compose run template-server sh
$ npm run lint # run linter
$ npm run lint:fix # run linter and fix errors
```


### Repository structure (Edit Later)

```
express-template/
+--server
```
