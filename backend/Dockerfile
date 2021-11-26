FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=services
ENV MONGODB_PASSWORD=shiv123

CMD ["npm", "start"]