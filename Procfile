release: python manage.py makemigrations && python manage.py migrate
web: gunicorn pg_api.wsgi