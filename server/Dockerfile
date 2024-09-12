FROM node:20.9.0-alpine

WORKDIR /app

RUN npm install -g npm@10.2.4

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 5000

CMD ["npm", "start"]