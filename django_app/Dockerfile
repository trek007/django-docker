FROM python:3.8.13-slim-buster

WORKDIR /demo

COPY requirements.txt .

RUN pip3 install -r requirements.txt

ADD . /demo

EXPOSE 8000

ENV PYTHONUNBUFFERED=1

CMD python3 manage.py runserver 0:8000



