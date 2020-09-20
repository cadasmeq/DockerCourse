FROM python:3

WORKDIR /app

COPY app.py requeriments.txt ./

RUN pip install -r ./requeriments.txt

CMD python app.py

EXPOSE 5000