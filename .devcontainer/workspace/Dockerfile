FROM openjdk:11-slim

RUN apt update && \
  apt install git curl vim -y && \
  curl -sL https://deb.nodesource.com/setup_16.x | bash - && \
  apt install nodejs -y && \
  npm i -g serverless@2