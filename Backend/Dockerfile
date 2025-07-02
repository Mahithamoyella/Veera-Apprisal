# Use Node base image
FROM node:18

# Create app directory
WORKDIR /app

# Install dependencies
COPY package*.json ./
RUN npm install

# Copy rest of the app
COPY . .

# Expose backend port
EXPOSE 3079

# Start server
CMD ["node", "server.js"]

