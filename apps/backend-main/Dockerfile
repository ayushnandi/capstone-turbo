FROM node:18-slim

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY dist ./dist

ENV PORT=5000

EXPOSE 5000

CMD [ "npm" , "start" ]