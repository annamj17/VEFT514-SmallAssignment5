FROM node:latest

LABEL maintainer="Anna Margret"

ENV NODE_ENV production

COPY . /app
WORKDIR /app
RUN npm install

EXPOSE 80
ENTRYPOINT [ "npm", "start" ]