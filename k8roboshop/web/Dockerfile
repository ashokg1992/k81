FROM nginx
RUN  rm -rf /usr/shaare/nginx/html/index.html
RUNrm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY default.conf /etc/nginx/nginx.conf
ADD static /usr/share/nginx/html/