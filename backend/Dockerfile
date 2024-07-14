FROM node:18-alpine

WORKDIR /app

COPY . .
RUN npm install --force

COPY .env.example .env
EXPOSE 3001

CMD ["npm", "run", "dev"]
