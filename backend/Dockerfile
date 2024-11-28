FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV USERNAME fabs
ENV PASSWORD example

CMD ["node", "app.js"]