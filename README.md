
# API 

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
