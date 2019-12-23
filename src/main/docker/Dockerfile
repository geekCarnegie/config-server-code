# Micro Service - Config Server
# Author GeekTech
# Version 1.0.0

FROM geekcarnegie/centos:1.0
MAINTAINER GeekTech
VOLUME /tmp
ADD config-server-1.0.0.jar config-server.jar
RUN bash -c 'touch /config-server.jar'
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar", "/config-server.jar"]