FROM node:14-alpine
WORKDIR /docker/todo-app/front-end/
COPY . /
ADD ./node_modules.tar.gz ./
ENTRYPOINT [ "npm", "install" ]
CMD ["npm", "start"]
EXPOSE 3000
