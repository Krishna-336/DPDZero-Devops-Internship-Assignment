FROM python:3.9-slim

WORKDIR /app

COPY . .

RUN pip install flask \
    && apt-get update && apt-get install -y curl

EXPOSE 8002

CMD ["python", "app.py"]

