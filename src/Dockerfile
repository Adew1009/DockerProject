FROM node:21-alpine

WORKDIR /Users/andrew-dew/projects/Docker-Todo/learn_docker/src/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]