# Use the official NGINX image
FROM nginx:latest

# Copy a custom NGINX configuration file
COPY nginx.conf /etc/nginx/nginx.conf

# Create a custom HTML file
COPY index.html /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Start NGINX
CMD ["nginx", "-g", "daemon off;"]
