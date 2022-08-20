python -m pip install virtualenv

python -m virtualenv venv

---
pip3 install virtualenv

virtualenv env

env\Scripts\activate.bat

pip3 install flask flask-sqlalchemy

python app.py -> to start the app

---
python -> to open terminal

from app import db

db.create_all() -> should create test.db

exit()

---
heroku login

---
pip3 install gunicorn -> dependency to freeze requirements

pip3 freeze > requirements.txt

---
git init

git add .

git commit -m 'flask todo app by fcc'

---
heroku create flask-crud-app-by-fcc -> add remote heroku

or heroku git:remote -a flask-crud-app-by-fcc

---
git remote -v

git push heroku master -> deploy to heroku

---
git remote add origin https://github.com/nightsailor/flask-app.git

git branch -M main

git push -u origin main -> upload to git

---
Procfile ->

gunicorn -> creates a web server

app -> what file to create a web server for
