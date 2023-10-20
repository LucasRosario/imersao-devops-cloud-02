FROM node:18.16.0
WORKDIR /app
COPY package*.json ./
RUN npm set strict-ssl false && npm install
COPY . .
EXPOSE 8082
CMD ["node", "server.js"]