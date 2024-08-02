FROM nginx:1.27.0
COPY ./default.conf /etc/nginx/conf.d/default.conf
COPY ./includes/ /etc/nginx/includes/
COPY ./ssl/ /etc/ssl/certs/nginx/
COPY ./page-not-found.html /var/www/html/page-not-found.html