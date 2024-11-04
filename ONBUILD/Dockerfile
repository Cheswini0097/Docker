FROM ubuntu:latest

# Update the package lists
RUN apt-get update -y

# Install Nginx
RUN apt-get install -y nginx

# Remove the default Nginx index.html
RUN rm -rf /usr/share/nginx/html/*

# Copy your custom index.html
COPY index.html /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]