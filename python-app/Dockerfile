FROM python:3.12-slim

WORKDIR /app

COPY app.py db.py requirements.txt ./

RUN pip install --no-cache-dir -r requirements.txt \
    && mkdir -p /app/data

EXPOSE 5000

