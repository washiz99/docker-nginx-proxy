FROM nginx:1.17.6
COPY nginx.conf /etc/nginx/nginx.conf

ADD ./certs/ssl.crt /etc/nginx/certs/ssl.crt
ADD ./certs/ssl.key /etc/nginx/certs/ssl.key

EXPOSE 443
EXPOSE 80
