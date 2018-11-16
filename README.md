# Python Interview Question

## Prerequisites

These should be installed / created before starting the question.

This task will be done in Python. You do not need to be fully fluent with enterprise production Python, but you should be comfortable with general syntax and patterns e.g. try/except.

It will be helpfulto have your IDE of choice set up with syntax highlighting for Python.

1. Make sure you have Python 2.7 installed. To check run `python --version`.
2. Install [Virtualenv](https://virtualenv.readthedocs.io/en/latest/index.html). You should be able to get it with `pip install virtualenv`
3. Install + configure git locally: https://help.github.com/articles/set-up-git/
4. Set up the development environment for flask.
    - `git clone https://github.com/pallets/flask.git`
    - `cd flask`
    - Create a virtualenv with `virtualenv env`.
    - Activate the virtualenv with `source env/bin/activate`.
    - Install the pinned dependencies included at `requirements.txt` in this repository by running `pip install -r requirements.txt`
    - Install the flask development dependencies `pip install -e ".[dev]"`
    - Make sure your IDE is set up to make code changes in the flask repository.
5. Check that the tests work by running `pytest tests` from the flask directory.
6. Familiarize yourself with flask. A great way is to read through http://flask.pocoo.org/docs/1.0/quickstart/.
