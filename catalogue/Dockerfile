FROM node:18
EXPOSE 8080
WORKDIR /opt/server
ENV MONGO=true
COPY package.json /opt/server/
COPY sever.js /opt/server/
RUN npm install
CMD ["node", "server.js"]