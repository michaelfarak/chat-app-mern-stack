FROM node:19.6.0
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY package.json /usr/src/app
RUN npm install
COPY . /usr/src/app/
EXPOSE 1337
CMD ["node", "index.js"]