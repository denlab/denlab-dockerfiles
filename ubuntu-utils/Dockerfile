FROM ubuntu:16.04

RUN apt-get update && apt-get install -y aptitude && \
    aptitude install -y                              \
        file                                         \
        curl wget                                    \
        openjdk-8-jdk-headless

WORKDIR /root
