web: gunicorn config.wsgi:application
worker: newrelic-admin run-program celery worker --app=Borges.taskapp --loglevel=info
