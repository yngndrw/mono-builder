FROM ubuntu:trusty
MAINTAINER yngndrw

RUN apt-get -q update
RUN apt-get -q -y install curl gcc g++ make wget unzip

COPY build build
CMD ./build

