FROM node:20-alpine

RUN mkdir -p /home/matvey/Docker_compose_app/app

COPY ./app /home/matvey/Docker_compose_app/app

WORKDIR /home/matvey/Docker_compose_app/app

RUN npm install 

CMD ["node", "server.js"]

