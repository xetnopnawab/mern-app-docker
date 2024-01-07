# FROM ubuntu:latest
FROM node:latest


COPY .  /home/app/

WORKDIR /home/app/

COPY package.json ./

RUN npm install 
CMD ["node", "./server.js"]

EXPOSE 4000
