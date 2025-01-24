web: gunicorn --bind :8000 --workers 3 Aconfig.wsgi:application 
release: python manage.py collectstatic --noinput