FROM nginx:stable-alpine
COPY templates/index.html /usr/share/nginx/html/
COPY static/ /usr/share/nginx/html/static/
COPY static/* /usr/share/nginx/html/static/
COPY nginx.conf /etc/nginx/nginx.conf
#ADD nginx.conf /etc/nginx/nginx.conf/nginx.conf
EXPOSE 80 443

