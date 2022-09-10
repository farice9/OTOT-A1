# Specify the base image to build from
FROM node:16

# Create app directory inside the image
WORKDIR /usr/src/app

# Install app dependencies (note that Node.js and NPM already installed with this image)
COPY package*.json ./
RUN npm install

# Bundle app source
COPY . .

# The app binds to port 8080, use EXPOSE to map it
# Expose provides hint for users of an image which port provides services
EXPOSE 8080

# Command to run the app
CMD ["node", "index.js"]