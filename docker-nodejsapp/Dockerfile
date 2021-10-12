#Base Image
FROM node

#Specifying the working directory in the image
WORKDIR /app

#copy the build output to the working directory
COPY . .

#restoring all the dependecnies
RUN npm install

#Exposing the required port
EXPOSE 9999

#starting the node application
CMD ["node", "server.js"]