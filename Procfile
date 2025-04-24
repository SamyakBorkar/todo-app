web: gunicorn To-DoApp.wsgi --log-file - 
#or works good with external database
web: python manage.py migrate && gunicorn To-DoApp.wsgi
