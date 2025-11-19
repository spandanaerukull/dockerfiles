FROM almalinux:9   
RUN dnf install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html 
COPY index.html /usr/share/nginx/html/index.html 
CMD ["nginx", "-g", "daemon off;"] 



##base image is almalinux version 9
##installing nginx web server
##removing default html page of nginx
##copying our custom html page to nginx html location
## running nginx in foreground
## daemon off; is used to run nginx forground
# FROM is used to tell our base image