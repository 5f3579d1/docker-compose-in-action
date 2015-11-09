FROM k/java

MAINTAINER k <5f3579d1@gmail.com>

RUN \
  curl -O http://mirrors.cnnic.cn/apache/tomcat/tomcat-8/v8.0.28/bin/apache-tomcat-8.0.28.tar.gz && \
  tar zxf apache-tomcat-*.tar.gz -C /usr/local/ && \
  rm apache-tomcat-*.tar.gz

EXPOSE 8080

ENTRYPOINT /usr/local/apache-tomcat-8.0.28/bin/catalina.sh start && tail -f /usr/local/apache-tomcat-8.0.28/logs/catalina.out

