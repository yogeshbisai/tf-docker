# base OS
FROM almalinux:8
RUN yum update -y
# Installing web server
RUN yum install nginx -y
RUN rm -rf  /usr/share/nginx/html/index.html
# copying app code to Image
COPY qa/ /usr/share/nginx/html/
# starting web server
CMD ["nginx", "-g", "daemon off;"] # CMD run the container n foreground
