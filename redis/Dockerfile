# Version: 0.0.1
FROM ubuntu:14.04
MAINTAINER xubai
ENV REFRESHED_AT 2015-09-09
RUN apt-get update
RUN apt-get -y install redis-server redis-tools
EXPOSE 6379
ENTRYPOINT [ "/usr/bin/redis-server" ]
CMD []
