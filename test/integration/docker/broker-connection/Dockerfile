FROM ubuntu:20.04

WORKDIR /opt

RUN apt-get update && apt-get install -y curl

ADD scripts/* ./
RUN chmod +x *
