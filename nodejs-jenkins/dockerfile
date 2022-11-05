FROM node:fermium-alpine3.16

RUN mkdir -p /app

WORKDIR /app

COPY main.js package.json /app

RUN npm install

COPY . /app

EXPOSE 8080

CMD ["npm", "run", "start"]
