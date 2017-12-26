FROM ubuntu:16.04

RUN sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv EA312927
RUN sudo apt-get update
RUN sudo apt-get install -y mongodb-org
RUN sudo systemctl start mongod
RUN curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash - sudo apt-get install -y nodejs
