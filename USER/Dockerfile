FROM almalinux:9
RUN dnf install nginx -y
RUN useradd nithin
USER nithin
CMD ["nginx", "-g", "daemon off;"]