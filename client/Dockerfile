FROM node:alpine

WORKDIR  /app

COPY package*.json ./

COPY  . .
#RUN npm cache clean --force

RUN npm install


CMD [ "npm start","npm test", "npm run build" ]





