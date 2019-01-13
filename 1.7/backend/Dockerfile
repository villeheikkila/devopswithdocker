FROM ubuntu

WORKDIR /backend-example-docker
COPY backend-example-docker .
EXPOSE 8000

RUN apt-get update && apt-get install -y curl gnupg2
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt-get install -y nodejs 

EXPOSE 8000

ENV FRONT_URL=http://localhost:5000

RUN npm install


