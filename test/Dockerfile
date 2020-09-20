FROM ubuntu

RUN apt update && apt install iputils-ping -y && apt install curl -y &&  apt install vim -y

COPY sandbox.txt /tmp/platzi
CMD ["ping","-c","5","www.google.cl"]