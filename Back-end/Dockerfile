FROM node:latest as build
WORKDIR /app

COPY ./ /app/
RUN npm install

CMD ["npm", "run", "start"]

EXPOSE 3000