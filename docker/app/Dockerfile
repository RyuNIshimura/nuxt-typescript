FROM node:10.15.3-alpine as node
ENV LANG C.UTF-8

RUN apk update && \
    apk add \
    vim \
    tree

ENV NODE_ENV development
ENV YARN_VERSION 1.9.2
ENV HOST 0.0.0.0

RUN mkdir /app
WORKDIR /app
COPY . /app

RUN yarn global add vue-cli
RUN yarn install

EXPOSE 4000

CMD ["yarn", "dev"]