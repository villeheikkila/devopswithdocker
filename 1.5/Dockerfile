FROM ubuntu

WORKDIR /frontend-example-docker
COPY frontend-example-docker .
RUN apt-get update && apt-get install -y curl gnupg2
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt-get install -y nodejs 
RUN npm install
