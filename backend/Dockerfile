FROM node:14-alpine3.12

//Added the below code
WORKDIR /app
COPY package*.json ./
RUN npm install --production
//
COPY . .
EXPOSE 3000
CMD ["node","index.js"]
