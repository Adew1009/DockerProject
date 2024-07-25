# Use a stable and supported Node.js version
FROM node:16-alpine

# Set a working directory within the container
WORKDIR /app

# Copy package.json and package-lock.json (if available)
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of your application code
COPY . .

# Expose port 3000 for the app
EXPOSE 3000

# Start the application
CMD ["npm", "start"]
