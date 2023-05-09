FROM node:17-alpine
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install 
COPY index.html .
COPY server.js .

Expose 3000 
CMD ["npm", "start"]
