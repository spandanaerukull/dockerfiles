FROM almalinux:9  #base image
RUN dnf install nginx -y # to install nginx
RUN rm -rf /usr/share/nginx/html/index.html  # to remove default html page
COPY index.html /usr/share/nginx/html/index.html #to copy our html page to nginx html location copy command:copy<source>destination
CMD ["nginx", "-g", "daemon off;"] # to run nginx in foreground