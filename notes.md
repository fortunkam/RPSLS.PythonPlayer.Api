pip install -r requirements.txt

gunicorn --workers 1 --threads 5 --bind :5000 --log-level info app:app

http://localhost:5000/healthcheck


test

test