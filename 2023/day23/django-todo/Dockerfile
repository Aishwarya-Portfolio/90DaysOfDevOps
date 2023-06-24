FROM python:3
RUN pip install Django==4.2.2
COPY ./2023/day23/django-todo/ .
RUN python manage.py migrate
CMD ["python", "manage.py", "runserver", "0.0.0.0:8005"]
