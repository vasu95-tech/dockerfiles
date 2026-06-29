FROM almalinux:9
RUN dnf install nginx -y
RUN sudo rm /usr/share/nginx/html/index.html
COPY sudo index.txt /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]
