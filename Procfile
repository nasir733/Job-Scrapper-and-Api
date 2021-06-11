web: gunicorn scrapper.wsgi
worker: celery -A scrapper worker -l info --pool=solo
workerbroker:celery -A scrapper beat -l INFO --scheduler django_celery_beat.schedulers:DatabaseScheduler