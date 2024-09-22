FROM debian:11

RUN apt update
RUN apt upgrade -y
RUN apt install php-fpm -y
RUN apt install wordpress -y

CMD ["tail", "-f"]
