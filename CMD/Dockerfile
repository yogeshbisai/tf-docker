FROM almalinux:8
RUN yum update -y
RUN yum install nginx -y
RUN echo "hello world from Aadhya" > /usr/share/nginx/html/hello.html
CMD ["nginx", "-g", "daemon off;"] # CMD run the container n foreground

