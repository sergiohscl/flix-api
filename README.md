# Project Flix (Cinema)
## Objetivo do projeto e implementar conceitos do Django-rest-framework.

#### Criar apis usando DRF;
#### Implementar o swagger;

<hr>

## Documentação do django
https://www.djangoproject.com/

## Instalando ambiente virtual
    python3 -m venv venv

## Ativando e desativando ambiente virtual
### Linux
    . venv/bin/activate
    deactivate

### Windows
    source venv\Scripts\Activate.ps1   # terminal powersheel        
    source venv\Scripts\Activate.bat   # terminal cmd

## Instalando django no ambiente virtual
    pip install django

## Iniciando project django
    django-admin startproject <nome-project> .

## Criar o arquivo requirements.txt
    pip freeze > requirements.txt

## Instale as dependências no projeto
    pip install -r requirements.txt

## Rodando django-admin
    python manage.py runserver

## Migrando a base de dados do Django
    python manage.py makemigrations
    python manage.py migrate

## Criando e modificando a senha de um super usuário
    python manage.py createsuperuser
    python manage.py changepassword USERNAME

## Criando apps
    python manage.py startapp <nome app>

## Importar o arquvivo .csv 
    python manage.py import_actors acotrs.csv
