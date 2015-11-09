# docker-compose-in-action

## install

    curl -sSL https://get.docker.com/ | sh

## config

 * /etc/default/docker

        DOCKER_OPTS='--icc=false --iptables=true'

## start

    docker-compose up

