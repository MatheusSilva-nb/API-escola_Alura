### Features

- [x] Cadastro de usuário
- [x] Cadastro de cursos
- [x] matrículas

# API 🚧 Em construção🚧

Api para cadastro de usuário, cursos e matriculas 

## Instalação 

Criação de ambiemte virtual 

```bash
python3 -m venv env
```
Ativar ambiente virtual
* Windows 
```bash
cd env/Scripts/activate
```
* linux
```bash
source env/bin/activate
```

instalar requerimentos

```bash
pip install -r requirements.txt
```


## Uso

Criação de usuário admin
```bash
python manage.py createsuperuser
```
fazer migrações antes de iniciar:

```bash
python manage.py migrate
```

Iniciar aplicação

```bash
python manage.py runserver
```


### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Django](https://docs.djangoproject.com/en/3.2/)
- [Django Rest framework](https://www.django-rest-framework.org/)
