FROM node:17

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

ENTRYPOINT [ "node" ]

CMD [ "app.js" ]

EXPOSE 3000
