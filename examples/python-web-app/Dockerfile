FROM python:3.10-slim

WORKDIR /app

COPY requirements.txt /app
COPY devops /app

RUN python -m pip install -r requirements.txt

ENTRYPOINT ["python"]
CMD ["manage.py", "runserver", "0.0.0.0:8000"]




