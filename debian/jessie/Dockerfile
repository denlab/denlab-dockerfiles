FROM debian:jessie

RUN apt-get update

RUN apt-get install -y aptitude

RUN echo 'deb http://ftp.de.debian.org/debian stretch main' >> /etc/apt/sources.list \
    && aptitude update

RUN aptitude install -y jq \
    && echo a | jq -rR '.' | grep -qx a
