FROM node:lts-alpine3.18

WORKDIR  /app

COPY package*.json ./

COPY  . .

RUN npm install

CMD [ "npm start","npm test", "npm run build" ]





