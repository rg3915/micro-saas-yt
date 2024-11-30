# micro-saas-yt

Micro SaaS para o YouTube

## Este projeto foi feito com:

* [Python 3.12.4](https://www.python.org/)
* [Django 5.1.3](https://www.djangoproject.com/)

## Como rodar o projeto?

* Clone esse repositório.
* Crie um virtualenv com Python 3.
* Ative o virtualenv.
* Instale as dependências.
* Rode as migrações.

```
git clone https://github.com/rg3915/micro-saas-yt.git
cd micro-saas-yt

python -m venv .venv
source .venv/bin/activate

pip install -r requirements.txt

python contrib/env_gen.py

python manage.py runserver
```
