FROM mhart/alpine-node:14
WORKDIR /usr/src/app
COPY package*.json ./
RUN yarn

#healthcheck
#RUN apk add curl

EXPOSE 3000
CMD [ "yarn", "run", "start:dev" ]