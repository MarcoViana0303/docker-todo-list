FROM node:14

EXPOSE 3001

ADD node_modules.tar.gz /

COPY routes.js server.js /docker/todo-app/back-end/src/api/
COPY Tasks.js /docker/todo-app/back-end/src/controllers/Tasks.js
COPY tasks.bkp.json tasks.json /docker/todo-app/back-end/src/database/
COPY Tasks.js /docker/todo-app/back-end/src/models/Tasks.js
COPY fileHandler.js /docker/todo-app/back-end/src/utils/fileHandler.js

ENTRYPOINT [ "npm start" ]