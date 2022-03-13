# Django-Tailwind starter
Commands to install dependencies:
```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py tailwind install
```

## To run server you need to run 2 servers
```
python manage.py tailwind start
python manage.py runserver
```