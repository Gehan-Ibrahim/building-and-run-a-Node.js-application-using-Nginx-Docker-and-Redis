FROM node:alpine
WORKDIR /usr/src/app
COPY package.json .
RUN npm install
COPY server.js .
COPY . .
CMD ["npm","start"]
