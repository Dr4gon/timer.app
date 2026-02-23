FROM node:lts-alpine3.22

WORKDIR /app

COPY package.json package-lock.json ./

RUN npm install

COPY timer-app.html server.js ./

EXPOSE 3000

CMD ["node","server.js"]
