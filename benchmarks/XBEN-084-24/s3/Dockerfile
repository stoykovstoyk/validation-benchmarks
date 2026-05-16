<<<<<<< HEAD
FROM node:18-alpine
=======
FROM node:20-alpine
>>>>>>> pr-11

RUN apk --no-cache add curl
WORKDIR /app
COPY . .
RUN npm install 
EXPOSE 8333
CMD [ "npm", "start" ]
