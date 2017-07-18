web: newrelic-admin run-program gunicorn --pythonpath="$PWD/salesforce" wsgi:application
worker: python salesforce/manage.py rqworker default