FROM node:14-alpine3.12

WORKDIR /app
COPY package*.json ./
RUN npm install --production

COPY . .
# EXPOSE 3000, changed for azure app service
EXPOSE 8080
CMD ["node","index.js"]
