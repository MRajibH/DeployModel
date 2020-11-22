Web: gunicorn DeployModel.wsgi --log-file -
web: python DeployModel/manage.py runserver 0.0.0.0:$PORT
heroku ps:scale web=1