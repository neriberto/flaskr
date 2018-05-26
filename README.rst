Flaskr
======

The tutorial can be found in http://flask.pocoo.org/docs/tutorial/

# Install

After clone the repository, create a virtualenv and activate it:

python 2.7

```bash
virtualenv venv
source venv/bin/activate
```

install Flaskr:

```bash
pip install -e .
```

# Run

```bash
export FLASK_APP=flaskr
export FLASK_ENV=development
flask run
```

Open http://127.0.0.1:5000 in a browser.

# Testing

```bash
pip install '.[test]'
pytest
```

Run with coverage report:

```bash
coverage run -m pytest
coverage report
coverage html  # open htmlcov/index.html in a browser
```