web: gunicorn schemalister.py --workers $WEB_CONCURRENCY
worker: celery -A getschema.tasks worker -B --loglevel=info
