FROM node:14
EXPOSE 8080
WORKDIR /opt/server
COPY package.json .
ADD server.js .
RUN npm install 
CMD ["node", "server.js"]