FROM node:20-alpine

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

ARG PORT
ENV PORT=$PORT

ARG MONGO_URI
ENV ENV PORT=$PORT=$ENV PORT=$PORT

EXPOSE 3000

CMD [ "node", "server.js" ]