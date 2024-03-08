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

<!-- *comado para rodar o projeto* -->

- python manage.py runserver

```bash
Nesse exercício vamos dar inicio a construção dos modelos do nosso portfólio.
Para esse exercício crie uma branch de models, adicione os modelos junto
com o arquivo de migração, e crie um Pull Request adicionando os
professores da EBAC como revisores do código
```
