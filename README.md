# Mini Curso de Django Básico

## Instalação

* Clone o repositório.
* Crie um virtualenv com Python 3.
* Ative o virtualenv.
* Instale as dependências.
* Configure a instância com o .env.
* Execute as migrações no banco de dados.
* Execute os testes.
* Rode a aplicação.

git clone https://github.com/seunome/djangotutorial.git
cd djangotutorial
python3 -m venv .venv
source .venv/bin/activate
# .venv\Scripts\activate.bat  # Windows
python -m pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
python manage.py test
python manage.py runserver
