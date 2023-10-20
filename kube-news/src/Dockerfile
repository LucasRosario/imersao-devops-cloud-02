FROM node:18.12.0
WORKDIR /app
COPY package*.json /app/
RUN npm set strict-ssl false
RUN npm install
COPY . .
EXPOSE 8082
CMD ["node", "server.js"]