# qa-docker-environment

This is a fairly simple docker container to facilitate development of WordPress plugins.

### Prerequisites

Mac users:
- [Docker Desktop](https://docs.docker.com/docker-for-mac/install/) includes everything you need.

## Setting up the container
#### 1. run `./start.sh`
This will create and start your containers. You can visit your environment by visiting `http://basic.wordpress.test` & `http://local.wordpress.test`. 

#### 2. Stopping and Starting the Environment
You can stop your environment by typing: `docker-compose down`
You can start your environment by typing: `docker-compose up`
You can start your environment without outputting logs by typing: `docker-compose up -d`
