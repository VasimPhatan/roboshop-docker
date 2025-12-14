FROM nginx
RUN rm -rf /usr/share/nginx/html/index.htnl
RUN rm -rf /etc/httpd/conf.d/default.conf
RUN rm -rf /etc/httpd/conf/nginx.conf
COPY roboshop.conf /etc/httpd/conf/nginx.conf
ADD static /usr/share/nginx/html
