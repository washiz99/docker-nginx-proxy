FROM nginx:1.17.6

COPY nginx.conf /etc/nginx/nginx.conf
COPY ssl.conf /etc/nginx/
COPY site.conf /etc/nginx/conf.d/sites-enabled/

COPY ./certs/ssl.crt /etc/nginx/certs/ssl.crt
COPY ./certs/ssl.key /etc/nginx/certs/ssl.key

EXPOSE 80 443

CMD ["nginx"]
