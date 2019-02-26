FROM django:latest

COPY django_project /usr/share/django_project
WORKDIR /usr/share/django_project

EXPOSE 8000

CMD ["python3", "manage.py", "runserver", "0.0.0.0:8000"]