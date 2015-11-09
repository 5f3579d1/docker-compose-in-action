FROM k/ubuntu

MAINTAINER k <5f3579d1@gmail.com>

RUN \
  apt-get update && \
  apt-get install -y nginx

RUN \
  ln -sf /dev/stdout /var/log/nginx/access.log && \
  ln -sf /dev/stderr /var/log/nginx/error.log

ADD nginx.conf /etc/nginx/

EXPOSE 80

ENTRYPOINT ["nginx"]

