# Use official Node.js base image
FROM node:18

# Create app directory
WORKDIR /app

# Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# Copy source files
COPY . .

# Expose the app port
EXPOSE 8081

# Run the app
CMD ["npm", "start"]
