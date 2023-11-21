FROM node

WORKDIR /app

# COPY package.json /app
COPY . /app

RUN npm install

EXPOSE 3000

CMD ["node","server.js"]