
#Variant #1 - Speculative: Install pre-baked container with node onboard aka AlpineNode

#Base image
FROM node:alpine


#Specify working directory
WORKDIR /usr/app

#Copy files from local storage inside the container
COPY ./package.json ./
#Install dependencies
RUN npm install

#Copy files from local storage inside the container
COPY ./ ./


#Default command
CMD ["npm", "start"]
