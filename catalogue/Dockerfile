FROM node:14

EXPOSE 8080

WORKDIR /opt/server

COPY package.json /opt/server/

#npm install gets all the dependencies for nodejs
RUN npm install

COPY server.js /opt/server/

CMD ["node", "server.js"]

