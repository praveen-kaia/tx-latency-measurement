FROM node:16

WORKDIR /usr/src/aptos

COPY . .

RUN npm install

CMD [ "node", "sendtx_aptos.js" ]
