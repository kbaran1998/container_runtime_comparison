FROM node:latest

WORKDIR /app

COPY ["package.json", "package-lock.json*", "main.js", "./"]

RUN npm install --production

CMD [ "node", "server.js" ]
