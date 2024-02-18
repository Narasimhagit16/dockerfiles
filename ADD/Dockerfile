FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/Narasimhagit16/shellscript/blob/main/IFS.sh > /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"]