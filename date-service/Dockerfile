FROM node:20

WORKDIR /app
COPY package*.json ./
RUN npm ci

COPY . .

EXPOSE 5005
CMD ["node", "date-service.js"]
