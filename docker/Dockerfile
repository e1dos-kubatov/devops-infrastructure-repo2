FROM python:3.11-slim

WORKDIR /app

COPY . .

RUN pip install flask

CMD ["python3", "-m", "http.server", "8000"]

