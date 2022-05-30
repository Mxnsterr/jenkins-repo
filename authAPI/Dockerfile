FROM node:latest

WORKDIR /authAPI

COPY package*.json ./
RUN npm install
COPY . .

EXPOSE 80

CMD ["node", "index.js"]