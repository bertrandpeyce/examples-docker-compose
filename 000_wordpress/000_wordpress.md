# Example Docker 000: Wordpress application

##  Description

In this example we will deploy a wordpress application with its mysql database.

##  Prerequisites

1. Install Docker, see official documentation for more information on how [here](https://docs.docker.com/engine/install/).  
2. Have sufficient disk space for wordpress application and database.
3. Have sufficient right access to install and run docker images.

## How to run this example

1. Pull the git projet `git@github.com:bertrandpeyce/examples-docker-compose.git`.  
2. Go in example folder `cd iac/examples/docker/000_wordpress`.  
3. Lancer Docker compose `docker compose up -d`.
4. Vérifier que les docker fonctionnent `docker ps`.
