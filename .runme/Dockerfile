FROM node:latest
WORKDIR /app
COPY . .
RUN npm install && npm rebuild node-sass
ENTRYPOINT npm run dev