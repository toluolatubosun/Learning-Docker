## Parent Image ##
FROM node:17-alpine 
# FROM node:latest

## Move to /app ##
WORKDIR /app

## Copy package.json ##
COPY package.json .

## Install dependencies ##
RUN npm install

## Copy app files from root to current directory (/app) ##
COPY . .

## Expose ports ##
EXPOSE 4000

## Run the app ##
CMD ["npm", "run", "dev"]
# CMD ["npm", "start"]