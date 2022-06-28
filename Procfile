release:python manage.py migrate
web: gunicorn chat.wsgi --log-file-= --log-level debug
python manage.py collectstatic --noinput
