# Specify a base image 
FROM node:alpine 

# Create working directory
WORKDIR /usr/app 

# Copy build directory 
COPY ./package.json ./ 

# Install some dependencies 
RUN npm install 

# Copy build directory 
COPY ./ ./ 

# Default command 
CMD ["npm", "start"]