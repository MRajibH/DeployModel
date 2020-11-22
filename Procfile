Web: gunicorn DeployModel.wsgi --log-file -
web: python Suicide_risk_checker/manage.py runserver 0.0.0.0:$PORT
heroku ps:scale web=1