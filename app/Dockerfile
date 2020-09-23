FROM python:3

MAINTAINER test@test.cl

VOLUME /prueba

WORKDIR /app

COPY app.py requeriments.txt ./

RUN pip install -r ./requeriments.txt && apt update && apt install net-tools -y

CMD python app.py

EXPOSE 5000