FROM debian:11

RUN apt update
RUN apt upgrade -y
RUN apt install nginx -y

CMD ["nginx", "-g", "daemon off;"]
