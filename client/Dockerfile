FROM node:latest
WORKDIR /client
RUN apt install git -y
RUN git clone https://github.com/petrlr14/CryptoPass
WORKDIR /client/CryptoPass
RUN npm install
EXPOSE 3000
CMD ["npm", "start"]