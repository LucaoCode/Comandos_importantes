# 🐍 Projetos em python

**-> Instalar o ambiente**
```shell
pip instal virtualenv
```
**-> Criando o ambiente virtual**
> Observação: Utilizar o prompt de comando e não o power shell.
```shell
virtualenv nome_ambiente
```
**-> Ativar o ambiente virtual**
> Observação: tem que estar na no diretorio Scripts do virtual env.
```shell
activate
```
**-> Gerar o requirements.txt para o ambiente**
```shell
pip freeze > requirements.txt
```

## 🔥 Django Framework

**->  Iniciar o django**
```shell
django-admin startproject app .
```

**->  Rodar o projeto django**
```shell
python manage.py runserver
```

**-> Cria o banco SQLite para o projeto**
```shell
python manage.py migrate
```

**-> adiciona as classes ao banco**
```shell
python manage.py makemigrate
```

**-> Cria um super usuário para o banco**
```shell
python manage.py createsuperuser admin
```

**-> cria um app responsável por uma parte do sistema**
```shell
python manage.py startapp core
```
