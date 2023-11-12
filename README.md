# django-first-project

Following the tutorials from the [official docs](https://docs.djangoproject.com/en/4.2/intro/tutorial01/).

## how to run 

General instructions about [virtualenv and pipenv](https://docs.python-guide.org/dev/virtualenvs/#virtualenvironments-ref).
First, setting up with virtualenv:
```bash
source venv/bin/activate
pip install -r requirements.txt

## for the first time we actually do
virtualenv venv # if not already created
python -m pip install Django
# .. installing other dependencies
pip freeze > requirements.txt # after installing
```
