FROM ubuntu

WORKDIR /frontend-example-docker
COPY frontend-example-docker .
RUN apt-get update && apt-get install -y curl gnupg2
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt-get install -y nodejs 

EXPOSE 5000

ENV API_URL=http://localhost:8000

RUN npm install
