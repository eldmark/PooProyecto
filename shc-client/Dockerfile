FROM node:18-alpine

WORKDIR /shc-client

COPY package.json ./
COPY package-lock.json ./

RUN npm ci

COPY . .

EXPOSE 5173

CMD ["npx", "expo", "start", "--web", "--port", "5173"]
