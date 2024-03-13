FROM python:3.11

WORKDIR /backend

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1


COPY ./requirements.txt /backend/
RUN pip install --no-cache-dir -r requirements.txt

COPY . .
