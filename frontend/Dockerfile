# its for development
FROM node:18.9.0-alpine

WORKDIR /app

COPY package.json .

RUN apk update
RUN yarn install

COPY . .

EXPOSE 3000

RUN yarn run build