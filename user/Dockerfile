FROM node:14
EXPOSE 8080
WORKDIR /opt/server
COPY server.js .
ADD package.json .
RUN npm install
ENV MONGO=true
CMD ["node", "server.js"]


