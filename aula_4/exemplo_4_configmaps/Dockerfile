FROM node:alpine

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

ENV MONGO_URL="uri"

COPY . .

EXPOSE 3000
CMD [ "npm","start" ]