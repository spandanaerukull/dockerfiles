FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://https://raw.githubusercontent.com/daws-84s/roboshop-infra-dev/refs/heads/main/30-vpn/data.tf /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]