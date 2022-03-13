# Django-Tailwind starter
Commands to install dependencies:
```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py tailwind install
```

## In settings.py you need to uncomment one of two lines
>NPM_BIN_PATH = r"C:\Program Files\nodejs\npm.cmd" - for Windows users
> 
>NPM_BIN_PATH = '/usr/local/bin/npm' - for Linux\Mac users

## To run server you need to run 2 servers
```
python manage.py tailwind start
python manage.py runserver
```