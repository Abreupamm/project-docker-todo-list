FROM node:14-alpine
COPY /todo-app/back-end /todo-app/back-end
ADD node_modules.tar.gz /todo-app/back-end/node_modules.tar.gz
EXPOSE 3001
RUN npm start