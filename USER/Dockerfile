FROM almalinux:9
RUN dnf install nginx -y
RUN useradd nithin
USER nithin
cmd ["nginx", "-g", "daemon off;"]