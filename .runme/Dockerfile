FROM node:latest
WORKDIR /app
COPY . .
RUN npm install && \
    npm rebuild node-sass && \
    npm run build  
ENTRYPOINT npm run dev 
