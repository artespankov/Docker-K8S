
#Variant #1 - Speculative: Install pre-baked container with node onboard aka AlpineNode

#Base image
FROM node:alpine

#Install dependencies
RUN npm install

#Default command
CMD ["npm", "run"]



## Variant #2 - Experimental. Dig into step-by-step dependencies management waterflow
#
## Base image
#FROM alpine
#
## Install npm
#RUN apk add --update npm
#
## Install dependencies
#RUN npm install
#
## Default command
#CMD ["npm", "run"]