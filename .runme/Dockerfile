FROM node:latest
WORKDIR /app
COPY . .
RUN npm install && npm rebuild node-sass && npm run dev && npm run http-server
ENTRYPOINT http-server ./public -p 8080 -a 0.0.0.0  to start on 0.0.0.0