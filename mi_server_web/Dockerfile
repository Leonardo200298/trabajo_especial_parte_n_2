FROM ubuntu:latest

RUN apt-get update && apt-get install -y nginx iproute2 ethtool iputils-ping

COPY index.html /var/www/html/

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
