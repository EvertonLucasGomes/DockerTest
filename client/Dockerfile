FROM node:16.13.0
WORKDIR /container/client
COPY *.json ./

RUN npm install @quasar/cli

RUN npm install
COPY . .

EXPOSE 8080