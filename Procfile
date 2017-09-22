web: gunicorn config.wsgi:application
worker: celery worker --app=stream_change.taskapp --loglevel=info
