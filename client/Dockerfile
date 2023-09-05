FROM node:lts-alpine3.18

#RUN  sudo apt update

WORKDIR  /app

COPY  . .

RUN npm install

CMD [ "npm start","npm test", "npm run build" ]





