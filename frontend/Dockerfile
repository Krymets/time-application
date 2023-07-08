FROM node:alpine

WORKDIR /app

EXPOSE 3000

COPY package*.json ./

COPY . ./

RUN npm install

CMD ["npm", "run", "dev"]