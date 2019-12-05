FROM python:3.8.0
ENV PYTHONUNBUFFERED 1
RUN mkdir /code
WORKDIR /code

RUN apt-get update && \
    apt-get install -y default-mysql-client
