Flaskr
======

The tutorial can be found in http://flask.pocoo.org/docs/tutorial/

Install
-------

After clone the repository, create a virtualenv and activate it:

python 2.7

::

    virtualenv venv
    source venv/bin/activate

install Flaskr:

::

    pip install -e .

Run
---

::

    export FLASK_APP=flaskr
    export FLASK_ENV=development
    flask init-db
    flask run

Open http://127.0.0.1:5000 in a browser.

Testing
-------

::

    pip install '.[test]'
    pytest

Run with coverage report:

::

    coverage run -m pytest
    coverage report
    coverage html  # open htmlcov/index.html in a browser

Building
--------

.. image:: https://travis-ci.org/neriberto/flaskr.svg?branch=master
    :target: https://travis-ci.org/neriberto/flaskr
