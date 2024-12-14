# Base image
FROM node

# Set working directory
WORKDIR /app

# Copy dependency files
COPY . .

# Install both production and dev dependencies (including nodemon)
RUN npm install 

# Expose port for the backend
EXPOSE 80


# Set the start command
CMD ["npm", "start"]
