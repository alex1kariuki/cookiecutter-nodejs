FROM node:latest

WORKDIR /app

COPY package.json .

# COPY yarn.lock .

RUN npm install 

COPY . .

EXPOSE $PORT

CMD npm run start:dev