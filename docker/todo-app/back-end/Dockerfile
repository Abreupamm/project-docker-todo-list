FROM node:14-alpine
COPY /todo-app/back-end ./todo-app/back-end
ADD node_modules.tar.gz ./todo-app/back-end
RUN npm start
EXPOSE 3001