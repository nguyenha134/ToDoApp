FROM node:latest

WORKDIR /app

COPY package*.json ./

RUN npm install -g npm@9.6.7 --silent

COPY . .

EXPOSE 4002

CMD ["npm", "run", "start"]