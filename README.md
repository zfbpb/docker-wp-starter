# WordPress on Docker starter
This guide will help you set up a Docker environment to run MySQL, phpMyAdmin, and WordPress using Docker Compose.

## Prerequisites
Before proceeding, make sure you have the following prerequisites installed on your system:
* Linux or WSL
* [Docker](https://www.docker.com/): Make sure Docker is installed and running on your machine.
* Make sure the following ports are not being used on the host machine:
    * `8020` - used by WordPress
    * `8183` - used by phpMyAdmin
    * `3306` - used by MySQL

## Installation
* Clone this repo
```
   cd (project directory)
   docker-compose up -d
```
