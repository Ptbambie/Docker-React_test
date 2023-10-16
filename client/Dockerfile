FROM node:lts-alpine

RUN mkdir /app
WORKDIR /app
COPY package*.json ./
RUN npm i
COPY ./public ./public

CMD npm start