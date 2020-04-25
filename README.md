# flask-practice
Flask practice (Flask(Jinja2, werkzeug), SQLAlchemy, sqlite3)

Run
```sh
$ export FLASK_APP=flaskr
$ export FLASK_ENV=development
$ flask init-db
$ flask run
```

Test
```sh
$ pip install '.[test]'
$ pytest
```

Run with coverage report:
```sh
$ coverage run -m pytest
$ coverage report
$ coverage html  # open htmlcov/index.html in a browser
```
