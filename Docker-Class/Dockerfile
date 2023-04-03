FROM node:18-alpine
# CMD node --version

WORKDIR /app

COPY package.json ./

RUN yarn

COPY . .

EXPOSE 5000

# CMD node index.js
