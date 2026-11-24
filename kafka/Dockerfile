FROM node:20-alpine

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install --omit=dev

COPY admin.js ./

USER node

CMD ["node", "admin.js"]
