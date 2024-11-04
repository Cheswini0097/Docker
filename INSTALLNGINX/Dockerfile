FROM ubuntu:latest

# Update the package lists
RUN apt-get update -y

# Install Nginx
RUN apt-get install -y nginx

# Expose port 80
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]