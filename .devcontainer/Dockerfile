# Use an official Node.js runtime as a parent image
FROM node:18

# Set the working directory inside the container
WORKDIR /usr/src/app

# Install Nest CLI globally
RUN npm install -g @nestjs/cli

# Copy the current directory contents into the container at /usr/src/app
COPY . .

# Install any needed packages specified in package.json
RUN npm ci

# Expose port 3000 to the outside world
EXPOSE 3000

# Command to run your application
CMD ["npm", "run", "start:dev"]
