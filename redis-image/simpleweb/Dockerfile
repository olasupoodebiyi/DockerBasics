# Specify a Base Image
FROM node:alpine

#Setup working directory
WORKDIR /usr/app

# Install some dependencies and Copy necessary files from local dir and 
COPY ./package.json ./
RUN npm install
COPY ./ ./



# Default Command
CMD ["npm", "start"]