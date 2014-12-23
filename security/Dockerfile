FROM dockerfile/nodejs

ENV FROM 2

RUN mkdir /app

ADD app /app

WORKDIR /app

RUN npm install

CMD ["node", "app.js"]