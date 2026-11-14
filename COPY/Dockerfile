FROM almarlinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY inder.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g" "daemon off;"]