FROM node:14-alpine
COPY . .
ADD node_modules.tar.gz ./todo-app/back-end
RUN npm install
RUN npm start
EXPOSE 3001