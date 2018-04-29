# Laravel on Docker

Build your Laravel application on Docker.

# Installation
Requirements
- You need to have [Docker](https://docs.docker.com/engine/installation/) installed

Run in root folder,
~~~~
docker-compose build && docker-compose up -d
~~~~

Login to the container,
~~~~
docker exec -it server /bin/bash -c "TERM=$TERM exec bash"
~~~~

# Maintainer Thanos Nokas
* [Thanos Nokas](https://www.linkedin.com/in/thanosnokas/)
