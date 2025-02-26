FROM almalinux:9
RUN dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]
RUN rm -rf /usr/share/nginx/html/index.html
COPY INDEX.HTML /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html