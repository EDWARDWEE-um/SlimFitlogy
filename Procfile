web: gunicorn LEAD_MANAGER_REACT_DJANGO.wsgi:application --log-file - --log-level debug
python manage.py collectstatic --noinput
manage.py migrate