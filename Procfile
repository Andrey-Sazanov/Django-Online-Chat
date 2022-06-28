release:python manage.py migrate
web: gunicorn chat.wsgi --log-file=-
python manage.py collectstatic --noinput
