# Use a lightweight web server as a base image. Nginx is perfect for static files.
FROM nginx:1.23-alpine

# Copy our single index.html file into the directory where Nginx serves files from.
COPY index.html /usr/share/nginx/html/index.html

# Nginx is already configured to start and listen on port 80, so we don't need to do anything else!