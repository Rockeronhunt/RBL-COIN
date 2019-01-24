FROM debian:stretch
LABEL maintainer="ROYALBRITISHLEGION Developers <dev@royalbritishlegion.org>"
LABEL description="Dockerised ROYALBRITISHLEGIONCore, built from Travis"

RUN apt-get update && apt-get -y upgrade && apt-get clean && rm -fr /var/cache/apt/*

COPY bin/* /usr/bin/
