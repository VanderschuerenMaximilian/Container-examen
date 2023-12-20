FROM python:3.12.0-alpine

WORKDIR /app

COPY . .

RUN apk add --no-cache postgresql-dev \
    && pip install -r requirements.txt

CMD ["python", "app.py"]