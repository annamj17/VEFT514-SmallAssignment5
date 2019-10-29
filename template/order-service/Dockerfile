FROM node:latest

LABEL maintainer="Anna Margret"

ENV NODE_ENV production

COPY . /app
WORKDIR /app
RUN npm install

ENTRYPOINT [ "npm", "start" ]