FROM nginx:latest

# copy static site into the container
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# copy nginx config
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
