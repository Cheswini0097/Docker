# Use a specific Ubuntu version for better reproducibility
FROM ubuntu:22.04

# Update the package lists
RUN apt-get update -y

# Install the Apache HTTP server
RUN apt-get install -y apache2

# Expose port 80 for HTTP traffic
EXPOSE 80

# Start the Apache HTTP server in the foreground
CMD ["apache2ctl", "-D", "FOREGROUND"]