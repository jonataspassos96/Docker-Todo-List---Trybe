FROM node:14-alpine AS todofrontend

WORKDIR /todo-list/frontend

COPY . .

ADD node_modules.tar.gz .

EXPOSE 3000

ENTRYPOINT [ "npm", "start" ]
