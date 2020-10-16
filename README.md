# Docker

Docker is a tool designed to make it easier to create, deploy, and run applications by using containers. Containers allow a developer to package up an application with all of the parts it needs, such as libraries and other dependencies, and deploy it as one package.

## Getting Started

These instructions will cover usage information and for the docker container 

### Prerequisities

In order to run this container you'll need docker installed.

* [Windows](https://docs.docker.com/windows/started)
* [OS X](https://docs.docker.com/mac/started/)
* [Linux](https://docs.docker.com/linux/started/)

### Usage

#### Docker Images

List all images

```shell
docker images
```

Delete images

```shell
docker rmi [IMAGE ID]
```

#### Docker Container

List all container

```shell
docker ps -a
```

Start docker container

```shell
docker start [options] container_id
```

You can specify the container by either using its name or ID (long or short).
To create a new container from an image and start it, use docker run:

```shell
docker run [options] image [command] [argument]

```

## Docker Compose

Compose is a tool for defining and running multi-container Docker applications.
With Compose, you use a Compose file to configure your application's services.
Then, using a single command, you create and start all the services
from your configuration. To learn more about all the features of Compose
see [the list of features](https://github.com/docker/docker.github.io/blob/master/compose/index.md#features).

Using Compose is basically a three-step process.

1. Define your app's environment with a `Dockerfile` so it can be
reproduced anywhere.
2. Define the services that make up your app in `docker-compose.yml` so
they can be run together in an isolated environment.
3. Lastly, run `docker-compose up` and Compose will start and run your entire app.

A `docker-compose.yml` looks like this:

    version: '3'

    services:
      web:
        build: .
        ports:
         - "5000:5000"
        volumes:
         - .:/code


## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<table border="0">
  <tr>
    <td align="center">
      <a href="https://github.com/mohammadalviyan">
        <img width="110" src="https://avatars1.githubusercontent.com/mohammadalviyan" alt="Mohammad Alviyan Anwari"><br/>
          <sub><b>Alviyan</b></sub>
      </a>
    </td>
  </tr>
</table>
<!-- ALL-CONTRIBUTORS-LIST:END -->