web: gunicorn chatapp.wsgi --log-file -
web2: daphne chatapp.asgi:application -p $PORT
worker: python manage.py runworker -v2
