Features
[x] Cadastro de usuário
[x] Cadastro de cursos
[x] matrículas
API 🚧 Em construção🚧
Api para cadastro de usuário, cursos e matriculas

Instalação
Criação de ambiemte virtual

python3 -m venv env
Ativar ambiente virtual

Windows
cd env/Scripts/activate
linux
source env/bin/activate
instalar requerimentos

pip install -r requirements.txt
Uso
Criação de usuário admin

python manage.py createsuperuser
fazer migrações antes de iniciar:

python manage.py migrate
Iniciar aplicação

python manage.py runserver
🛠 Tecnologias
As seguintes ferramentas foram usadas na construção do projeto:

Django
Django Rest framework
