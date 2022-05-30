FROM node:latest

WORKDIR /chatAPI

COPY package*.json ./
RUN npm install
COPY . .

EXPOSE 80

CMD ["node", "index.js"]