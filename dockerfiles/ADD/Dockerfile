FROM almalinux
RUN yum install nginx -yum
RUN rm -rf /usr/share/nginx/html/index.html
COPY 2 /usr/share/nginx/html/
CMD ["nginx","-g","daemon off;"]