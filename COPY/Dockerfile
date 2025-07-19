FROM almalinux:9  
RUN dnf install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html 
COPY index.html /usr/share/nginx/html/index.html 
CMD ["nginx", "-g", "daemon off;"] 



##base image
##install nginx
##remove default html page
##copy our html page to nginx html location
##run nginx in foreground
#daemon off means it will run in foreground
  