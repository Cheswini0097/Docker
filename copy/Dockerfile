FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /root/Docker/ARG/Dockerfile
CMD ["nginx", "-g", "daemon off;"]