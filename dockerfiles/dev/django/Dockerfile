
FROM python:3.10-slim-buster

LABEL maintainer="z.soofi.n@gmail.com"

ENV PYTHONUNBUFFERED=1

WORKDIR /app

COPY ./requirements.txt .

RUN pip imstall --upgrade pip && \
    pip install -r requirements.txt

COPY ./core .
