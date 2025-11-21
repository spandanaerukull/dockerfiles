FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]

# ONBUILD is trigger instruction it will not execute when we build this image, it will execute when we use this image as base image for other dockerfiles
# so when we use this image as base image for other dockerfiles it will copy index.html to nginx html location
# so we can create multiple images using this image as base image and each image can have different html pages
# so this is used to create base image for our application images

# onbuild instruction is mostly used to create base images for our application images
# here we are creating a base image which has nginx installed and when we use this image as base image for other dockerfiles it will copy index.html to nginx html location