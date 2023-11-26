FROM almalinux:8
# almalinux is same as centos
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
RUN echo "Hello World" > /usr/share/nginx/html/index.html
#daemon off command makes our container running and attached to screen
ENTRYPOINT [ "nginx", "-g", "daemon off;" ]