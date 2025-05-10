FROM node:18

WORKDIR /usr/src/app

COPY package*.json .

RUN npm install

COPY . .

ENV PORT=3000  \
    API_HOST=http://52.70.162.31:3001

EXPOSE 3000

CMD ["npm", "start"]
