
FROM node:14-alpine

WORKDIR /app

COPY package*.json ./

RUN npm install
RUN npm install --save-dev nodemon
RUN npm install express

COPY . .

CMD ["npm", "run", "dev"]