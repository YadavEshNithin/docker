FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/
ADD https://github.com/daws-84s/notes/blob/main/session-51.txt /usr/share/nginx/html/index.html
RUN chmod +r usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]