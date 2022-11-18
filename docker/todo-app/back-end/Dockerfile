FROM node:14-alpine as todobackend

WORKDIR /

EXPOSE 3001

ADD node_modules.tar.gz .

COPY . .

ENTRYPOINT [ "npm start" ]