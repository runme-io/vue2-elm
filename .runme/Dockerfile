FROM node:latest
WORKDIR /app
COPY . .
RUN npm install && npm install http-server
RUN npm rebuild node-sass 
RUN npm run build  
ENTRYPOINT http-server ./public -p 80 -a 0.0.0.0