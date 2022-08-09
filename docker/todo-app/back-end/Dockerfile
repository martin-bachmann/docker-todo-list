FROM node:14-alpine
WORKDIR /docker/todo-app/back-end

ADD node_modules.tar.gz .
EXPOSE 3001

COPY . .
ENTRYPOINT [ "npm" ]
CMD [ "start" ]