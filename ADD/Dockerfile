FROM almalinux:9
RUN dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]
RUN rm -rf /usr/share/nginx/html/index.html
ADD sample-1.tar /tmp/
ADD https://raw.githubusercontent.com/daws-81s/concepts/refs/heads/main/resize-disk.md  /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html