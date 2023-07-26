FROM nginx

COPY ./server.crt /etc/nginx/ssl/server.crt
COPY ./server.key /etc/nginx/ssl/server.key
COPY ./server.password /etc/nginx/ssl/server.password
COPY ./ssl.conf /etc/nginx/conf.d/ssl.conf

EXPOSE 443