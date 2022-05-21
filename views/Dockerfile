FROM node:10.15.0-alpine

WORKDIR /usr/src/app

COPY ./package.json ./
COPY ./package-lock.json ./

RUN npm install


COPY . .


EXPOSE 3000


CMD ["npm", "start" , "client"]