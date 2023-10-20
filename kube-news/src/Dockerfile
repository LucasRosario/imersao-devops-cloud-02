FROM node:18.12.0
WORKDIR /app
RUN ls
COPY package*.json /app/
RUN npm set strict-ssl false && npm install
COPY . .
EXPOSE 8082
CMD ["node", "server.js"]