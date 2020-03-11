FROM nginx:alpine
MAINTAINER from liujunandzhou liujunandzhou@163.com

ADD nginx.conf /etc/nginx/nginx.conf
ADD vhosts /etc/nginx/vhosts

CMD ["/usr/sbin/nginx","-g","daemon off;"]


