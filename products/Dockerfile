FROM node:17-alpine
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install 
COPY server.js .

Expose 3001 
CMD ["npm", "start"]