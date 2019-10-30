FROM node:latest

LABEL maintainer="Anna Margret"

ENV NODE_ENV=production
ENV PORT=80

COPY . /app
WORKDIR /app
RUN npm install

ENTRYPOINT [ "npm", "start" ]