# Nginx Build
From nginx:alpine

MAINTAINER yaechanKim <burgund32@gmail.com>

# Erase Default config
RUN rm -rf /etc/nginx/conf.d

COPY ./speechProxy/conf /etc/nginx

WORKDIR /usr/share/nginx/html

EXPOSE 3000

CMD ["/usr/sbin/nginx"]
