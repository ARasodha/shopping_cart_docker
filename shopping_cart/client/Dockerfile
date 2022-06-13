FROM node:14-slim

WORKDIR /app

COPY ./package.json ./
COPY ./package.lock.json ./
RUN npm install 
RUN npm install react-scripts@4.0.3 -g

COPY . ./
CMD ["npm", "start"]