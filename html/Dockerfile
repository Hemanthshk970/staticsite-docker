# Use official Nginx image as base
FROM nginx:alpine

# Set working directory inside container
WORKDIR /usr/share/nginx/html

# Copy your static website files (HTML, CSS, JS) into container
COPY . .

# Expose port 80
EXPOSE 80

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]

