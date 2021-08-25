FROM nginx

COPY ./default.conf /etc/nginx/conf.d/default.conf

COPY ./backend-not-found.html /var/www/html/backend-not-found.html

COPY ./includes/ /etc/nginx/includes/

COPY ./ssl/certs/ /etc/ssl/certs/nginx/

COPY ./ssl/private/ /etc/ssl/private/nginx/
