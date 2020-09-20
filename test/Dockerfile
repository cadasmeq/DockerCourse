FROM ubuntu

RUN apt update && apt install jp2a -y

ADD https://imagenes.20minutos.es/files/image_656_370/uploads/imagenes/2020/01/29/meme-de-una-mujer-gritando-me-dijiste-que-a-un-gato.jpeg /tmp/img.jpg

ENV TERM xterm-256color
CMD jp2a --size=60x40 /tmp/img.jpg

