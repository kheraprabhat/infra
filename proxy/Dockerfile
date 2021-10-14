FROM nginx

COPY ./nginx/dhparam.pem /etc/nginx/dhparam.pem
COPY ./nginx/nginx-selfsigned.crt /etc/ssl/certs/nginx-selfsigned.crt
COPY ./nginx/nginx-selfsigned.key /etc/ssl/private/nginx-selfsigned.key

COPY ./nginx/selfsigned.conf /etc/nginx/snippets/selfsigned.conf

COPY ./nginx/nginx.conf /etc/nginx/conf.d/default.conf