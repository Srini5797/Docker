FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/html.latest
COPY index.html /usr/share/nginx/html/html.latest
CMD ["nginx","-g","daemon off;"]