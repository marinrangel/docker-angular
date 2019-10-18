# use this dockerfile to build an image for this api

FROM node:10

WORKDIR /usr/src/app

COPY package*.json ./

RUN yarn install && yarn global add @angular/cli

COPY . /usr/src/app

EXPOSE 4200 49153

CMD [ "yarn", "start" ]