FROM mjgargani/puppeteer:trybe1.0
WORKDIR /docker/todo-app/tests/
COPY . /
ADD ./node_modules.tar.gz ./
ENTRYPOINT ["npm", "install"]
CMD ["npm", "test"]
