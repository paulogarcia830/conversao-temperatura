# Sempre user a tag de versionamento
# Usar somente images oficiais ou que vc mesmo fez

FROM node:16.16.0  
WORKDIR /app
COPY ./package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD [ "node", "server.js" ]