web: gunicorn schemalister.wsgi --workers $WEB_CONCURRENCY --preload
worker: celery -A getschema.tasks worker -B --loglevel=info
