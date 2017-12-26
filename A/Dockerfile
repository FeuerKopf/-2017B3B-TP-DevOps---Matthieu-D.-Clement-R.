FROM ubuntu:16.04

RUN apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv EA312927
RUN apt-get update
RUN apt-get install -y mongodb
RUN apt-get install --yes curl
RUN curl --silent --location https://deb.nodesource.com/setup_4.x
RUN bash -
RUN apt-get install --yes nodejs
RUN apt-get install --yes build-essential
