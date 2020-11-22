web: gunicorn schemalister.wsgi --workers --preload $WEB_CONCURRENCY
worker: celery -A getschema.tasks worker -B --loglevel=info
