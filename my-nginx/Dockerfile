FROM nginx:latest

RUN apt-get update -y \
	&& mkdir -p /home/pierrecardinvn.com/public_html 

COPY ./pierrecardinvn.com.conf /etc/nginx/conf.d/
COPY ./my-nginx.conf /etc/nginx/nginx.conf

EXPOSE 80 443
