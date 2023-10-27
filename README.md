# heroku_frontend
Heroku Frontend

gunicorn -k uvicorn.workers.UvicornWorker --bind 0.0.0.0:8080 main:app

twistd -n web --path httpdocs

https://shm-frontend-c3f2dc0fa89c.herokuapp.com/

https://shm-frontend-c3f2dc0fa89c.herokuapp.com/httpdocs/