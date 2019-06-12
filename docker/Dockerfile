FROM python:3.6-alpine3.9

ENV FLASK_APP app.py

RUN mkdir -p /app

WORKDIR /app

COPY ./ .

RUN pip install -r requirements.txt

ENTRYPOINT flask run -h 0.0.0.0 -p 5000