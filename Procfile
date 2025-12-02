release: python manage.py migrate --noinput
web: gunicorn ll_project.wsgi:application --bind 0.0.0.0:$PORT