web: newrelic-admin run-program gunicorn --pythonpath="$PWD/DrawingofZones" wsgi:application
worker: python DrawingofZones/manage.py rqworker default