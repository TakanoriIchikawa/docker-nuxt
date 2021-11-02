FROM node:16.13.0-alpine

RUN apk update && \
  apk add vim && \
  apk add git

RUN npm install --global @vue/cli @vue/cli-service-global @vue/cli-init

WORKDIR /src