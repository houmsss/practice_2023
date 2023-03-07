FROM node:18.10.0-alpine as build
WORKDIR /client

COPY package*.json ./

RUN npm install --legacy-peer-deps

COPY . .

EXPOSE 3001

CMD npm start