FROM python:3.9.16-slim

WORKDIR /var/www/html/mysite

RUN python -m pip install Django

ENTRYPOINT ["python", "manage.py", "runserver", "0.0.0.0:8000"]
