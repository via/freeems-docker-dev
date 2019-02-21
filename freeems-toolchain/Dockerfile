FROM debian:8

RUN dpkg --add-architecture i386
RUN echo 'deb http://debs.diyefi.org css-debs binary' >> /etc/apt/sources.list
RUN apt-get update && apt-get install -y git build-essential
RUN apt-get install -y --force-yes freeems-toolchain

RUN mkdir /freeems
WORKDIR /freeems

