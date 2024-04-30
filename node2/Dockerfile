FROM node:12

COPY package.json ./app/
COPY src ./app/

WORKDIR /app

RUN npm install 

ENV PORT=8080

EXPOSE 8080

CMD ["npm", "start"]