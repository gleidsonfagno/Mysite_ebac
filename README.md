# mysite

Django Personal Blog

## criando abiente virtual

- python3 -m venv env

## nova brach

- git checkout -b "project-setup"

## criar op my syte

- django-admin startproject mysite ou python -m django startproject mysite

## renomea o app para blog

- python manage.py startapp blog

## vai no aquivo settings.py

INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    <!-- 'blog', adiciona essa parte  -->
]

### na pasta mysite

- python manage.py migrate
- python manage.py makemigrations

<!-- *comado para rodar o projeto*livro de prog -->

- python manage.py runserver

```bash
Nesse exercício vamos dar inicio a construção dos modelos do nosso portfólio.
Para esse exercício crie uma branch de models, adicione os modelos junto
com o arquivo de migração, e crie um Pull Request adicionando os
professores da EBAC como revisores do código
```

## modulo 2

python manage.py createsuperuser

```bash
Username (leave blank to use 'empreendedor'): gleidsonfagno  
Email address: gleidsonfagno@gmail.com
Password: 123456
Password (again): 
This password is too short. It must contain at least 8 characters.
This password is too common.
This password is entirely numeric.
Bypass password validation and create user
```

- python manage.py shell

```shel
from blog.models import Post

from django.contrib.auth.models import User

```
