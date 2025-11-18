web: python3 backend/manage.py migrate && python3 backend/manage.py ensure_admin && gunicorn mediation_crm.wsgi:application --chdir backend --bind 0.0.0.0:$PORT

