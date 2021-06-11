web: gunicorn scrapper.wsgi
worker: celery -A scrapper beat -l INFO --scheduler django_celery_beat.schedulers:DatabaseScheduler
