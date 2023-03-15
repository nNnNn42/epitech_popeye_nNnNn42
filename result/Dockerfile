FROM node:12-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install && rm -rf /app/node_modules
COPY . .
EXPOSE 80
CMD ["node", "server.js"]
