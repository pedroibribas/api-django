# boilr-api-django
um boillerplate para api django

## inicializar projeto localmente (windows)
```shell
git clone https://github.com/pedroibribas/boilr-api-django.git
cd boilr-api-django
py -m venv ./venv
venv\Scripts\activate.bat
pip install -r requirements.txt
py manage.py runserver
```

## atualizar projeto
### criar app
```shell
python manage.py startapp my-app
```
### instalar dependência
```shell
pip install dependência
pip freeze > requirements.txt
```
