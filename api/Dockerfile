FROM node:alpine

WORKDIR /api

COPY . .

RUN npm install

EXPOSE 5000

CMD ["npm", "run", "dev"]