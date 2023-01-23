FROM python:3.9.9-slim-buster
ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1
WORKDIR /boilerplate
COPY requirements.txt /boilerplate/
RUN pip install -r requirements.txt
COPY manage.py /boilerplate
COPY . /boilerplate/