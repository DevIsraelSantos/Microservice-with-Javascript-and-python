FROM node:17-slim

COPY package*.json .

WORKDIR /app

RUN npm install

COPY . .

EXPOSE 3000

CMD [ "npm", "start" ]