# docker-mysql-phpmyadmin

Example to run MySQL and phpMyAdmin with Docker Compose.

## Prerequisites
[Install Docker](https://docs.docker.com/manuals/)

## Usage
1. Clone the repo
```
git clone git@github.com:garyhuang03/docker-mysql-phpmyadmin.git
cd docker-mysql-phpmyadmin
```
2. Create a docker network named "shared"
```
docker network create shared
```
3. Launch the containers
```
docker compose up -d
```
4. Point browser to: http://localhost:8081 (phpMyAdmin homepage) 