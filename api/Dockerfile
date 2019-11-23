FROM node:latest
WORKDIR /api
RUN apt install git -y
RUN git clone https://github.com/petrlr14/CryptoPassAPI
WORKDIR /api/CryptoPassAPI
RUN npm install
EXPOSE 3500
CMD ["npm", "start"]
