FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/daws-84s/roboshop-infra-dev/refs/heads/main/30-vpn/data.tf /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"] 

# ADD is used to add files from url or local system to our container

# CMD is just command to run this file 