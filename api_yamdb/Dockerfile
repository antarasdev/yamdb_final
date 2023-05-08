FROM python:3.7-slim
WORKDIR /app
COPY requirements.txt /app
COPY ./static/redoc.yaml ./static/
RUN pip3 install -r /app/requirements.txt --no-cache-dir
COPY ./../ /app
