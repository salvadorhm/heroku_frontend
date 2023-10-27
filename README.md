# heroku_frontend
Heroku Frontend

gunicorn -k uvicorn.workers.UvicornWorker --bind 0.0.0.0:8080 main:app

twistd -n web --path httpdocs