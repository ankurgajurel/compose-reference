FROM python:3.8-alpine

WORKDIR /app

COPY . .

RUN pip install -r requirements.txt

EXPOSE 3001

CMD ["python", "app.py"]