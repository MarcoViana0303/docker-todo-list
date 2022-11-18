FROM node:14-alpine as todofrontend

WORKDIR /

EXPOSE 3000

ADD node_modules.tar.gz .

COPY . .

ENTRYPOINT [ "npm start" ]