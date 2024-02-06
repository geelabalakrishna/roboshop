FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
COPY default.conf /etc/nginx/default.d/roboshop.conf
ADD static /usr/share/nginx/html/
