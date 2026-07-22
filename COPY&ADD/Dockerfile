FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/mamatha1823/Docker/blob/main/readme.MD /usr/share/nginx/html/index.html
COPY /tmp/xyz.txt /usr/share/nginx/html/index.html