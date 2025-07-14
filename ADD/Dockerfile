FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/
ADD blob:https://github.com/8db85dc5-ae86-4d8d-bdcf-6432dfa72a71 /usr/share/nginx/html/index.html
RUN chmod +r usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]