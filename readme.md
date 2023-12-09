## DJANGO


# Iniciar um novo enviroment
python -m venv venv

# Ativar o enviroment
source venv/bin/activate

# Instalar o Django
pip install django

# Criar um projeto django
django-admin startproject nome_projeto

# Criando um app
python manage.py startapp blog


# Criando uma migration a partir de um model
python manage.py makemigrations blog


# Criar super usuário
python manage.py createsuperuser

# Rodar projeto
python manage.py runserver
