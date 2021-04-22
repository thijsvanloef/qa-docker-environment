# qa-docker-environment

This is a fairly simple docker container to facilitate development of WordPress plugins.

### Prerequisites

Mac users:
- [Docker Desktop](https://docs.docker.com/docker-for-mac/install/) includes everything you need.

Windows
- [Docker Desktop](https://docs.docker.com/docker-for-windows/install/) includes most things you need.
- [GitExtensions](https://github.com/gitextensions/gitextensions/releases/) includes some unix tools we need.
- [GSudo](https://github.com/gerardog/gsudo) allows shell scripts to use sudo command on windows

Otherwise install:
- [Docker](https://docs.docker.com/v17.09/engine/installation/)
- [docker-compose](https://docs.docker.com/compose/install/)
- make sure your platform understands the sudo command
- friendly dns names (e.g. basic.wordpress.test) will not work out of the box

## Setting up the container
#### 1. run `./start.sh`
This will create and start your containers. You can visit your environment by visiting `http://basic.wordpress.test` & `http://local.wordpress.test`. 

#### Stopping and Starting the Environment
You can stop your environment by typing: `docker-compose down`
You can start your environment by typing: `docker-compose up`
You can start your environment without outputting logs by typing: `docker-compose up -d`