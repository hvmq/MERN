FROM node:20-alpine

WORKDIR /app/client

COPY package.json package-lock.json ./

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]