FROM node:alpine

ENV MONGO_DB_USERNAME=rohan \
    MONGO_DB_PWD=123456

WORKDIR /src

COPY ./src/package.json .
RUN npm install

COPY ./src .

CMD ["node", "app.js"]
