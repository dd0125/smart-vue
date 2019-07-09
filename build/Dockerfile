FROM node:8.16

ENV TZ Asia/Tokyo

RUN apt update

RUN npm install -g yarn
RUN yarn global add @vue/cli
RUN vue --version

RUN yarn add webpack
RUN yarn add webpack-dev-server


