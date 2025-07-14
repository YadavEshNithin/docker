FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY templatemo_591_villa_agency/ /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"]