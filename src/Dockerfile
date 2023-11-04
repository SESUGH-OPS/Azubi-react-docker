#Use and official nodejs runtime image as base image
FROM node:14


# set working directory
WORKDIR /app

#copy packages
COPY package*.json ./


#Install dependencies
RUN npm install 

#Copy rest of the files
COPY . .


#Expose port
EXPOSE 3000

#start the app
CMD [ "npm", "start" ]