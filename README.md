# flask-quickstart


repo for barebones to deploy a flask server on heroku


assuming that we are using miniconda3 as the package manager


create our flask environment and install flask


`conda create --name flask-env`


`conda install Flask`


run locally (not for prod)


`FLASK_APP=app.py flask run`



### deploying on Heroku

use gunicorn to deploy Flask app for prod
* requirements.txt
* runtime.txt
* Procfile


`heroku create`
