FROM node:lts-alpine

RUN mkdir -p /home

WORKDIR /home

COPY package*.json ./

RUN yarn

COPY . /home

EXPOSE 7000

CMD ["yarn","watch"]