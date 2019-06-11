FROM python:3.7-slim

RUN python -m pip install --upgrade pip

COPY requirements.txt requirements.txt
RUN python -m pip install -r requirements.txt

RUN mkdir /app
WORKDIR /app
COPY . /app