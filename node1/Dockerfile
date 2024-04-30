#install node
FROM node:18

#copy dari local directory to filesystem pada container 
# <src> <dst>
COPY package.json /app/
COPY src /app/

#seperti cd ...
WORKDIR /app

#karena kita butuh dependencies express, kita harus jalanin npm install 
#run any command in a shell inside container
RUN npm install

#last command in dockerfile
CMD ["node", "server.js"]