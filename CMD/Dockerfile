FROM almalinux:8
# almalinux is same as centos
RUN yum install nginx -y
RUN echo "Hello World" > /usr/share/nginx/hello.html
#daemon off command makes our container running and attached to screen
CMD [ "nginx", "-g", "daemon off;" ]