Iniciar o projeto Django

```
uv venv -p 3.13
source .venv/bin/activate
uv pip install django
django-admin startproject core .
python manage.py startapp contact

```

Configurar o git

```
git config --global user.name 'Seu nome'
git config --global user.email 'seu_email@gmail.com'
git config --global init.defaultBranch main
# Configure o .gitignore
git init
git add .
git commit -m 'Mensagem'
git remote add origin URL_DO_GIT

```

Migrando a base de dados do Django

```
python manage.py makemigrations
python manage.py migrate
```

Criando e modificandoa senha de um super usuário Django

```
python manage.py createsuperuser
python manage.py changepassword USERNAME
```
