web: gunicorn scrapper.wsgi
worker: celery -A scrapper worker -l info --pool=solo