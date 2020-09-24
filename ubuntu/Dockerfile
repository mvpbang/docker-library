FROM ubuntu:xenial
MAINTAINER mvpbang mvpbang@163.com
ADD sources.list /etc/apt/sources.list
RUN apt-get update -q && \
    apt-get install -y apt-utils inetutils-ping netcat-traditional net-tools curl wget && \
    apt-get clean