FROM ubuntu:14.04

MAINTAINER k <5f3579d1@gmail.com>

RUN \
  echo "deb http://mirrors.163.com/ubuntu/ trusty main restricted universe multiverse" > /etc/apt/sources.list && \
  apt-get update && \
  apt-get -y upgrade && \
  apt-get install -y software-properties-common && \
  apt-get install -y curl && \
  rm -rf /var/lib/apt/lists/*

