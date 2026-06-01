
FROM node:20-alpine

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY  . .

EXPOSE 5000

CMD ["node", "server.js"]











# FROM node:20-alpine
#         ↓
# Buying a furnished apartment

# COPY your code
# RUN npm install
#         ↓
# Adding your furniture and belongings

# docker build
#         ↓
# Your customized apartment