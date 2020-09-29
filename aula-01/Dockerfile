FROM node:alpine3.11
WORKDIR /app/aula-01
COPY package*.json .
RUN npm install
COPY . .
ENTRYPOINT [ "node", "index.js" ]
