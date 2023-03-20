# docs
#CRIAR APLICAÇÃO DJANGO
1 - Criar ambiente Virtual: python3 -m venv .nome_do_ambiente_virtual or python -m venv .nome_do_ambiente_virtual
2 - Ativar ambiente virtual: source nome_do_ambiente/bin/activate or nome_do_ambiente_virtual/Script/Activate
3 - Replicar ambiente em outras máquinas: pip freeze > requirements.txt. Se desejar rodar o projeto em outra máquina: pip install -r requirements.txt
4 - Instalar o Django: python -m pip install django.
5 - Criar o projeto: django-admin.exe startproject nome_projeto .
6 - criar Banco: python manage.py makemigrations => python manage.py migrate
7 - Criar superUser: python manage.py createsuperuser.
8 - rodar o projeto: python manage.py runserver
9 - Criar Apps: python manage.py startapp nome_do_app
