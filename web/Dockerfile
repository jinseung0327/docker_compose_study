FROM node:14-alpine

WORKDIR /usr/src/app

RUN npm install

COPY package*.json ./

COPY . .

EXPOSE 3000

CMD ["node", "app.js"]
