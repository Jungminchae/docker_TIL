FROM ubuntu:18.04

RUN apt-get update -y

RUN apt-get install apache2 -y

EXPOSE 80

# shell 형식
CMD apachectl -D FOREGROUND

# exec 형식 -> 다른 쉘을 할당하거나 다른 인자를 넘겨줄 때 사용
CMD ["apachectl", "-D", "FOREGROUND"]