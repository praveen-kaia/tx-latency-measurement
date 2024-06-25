FROM node:16

WORKDIR /usr/src/sui

COPY . .

RUN npm install

CMD [ "node", "sendtx_sui.js" ]
