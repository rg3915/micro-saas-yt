# micro-saas-yt

Micro SaaS para o YouTube

## Este projeto foi feito com:

* [Python 3.12.4](https://www.python.org/)
* [Django 5.0.7](https://www.djangoproject.com/)
* [Django-Ninja 1.2.1](https://django-ninja.dev/)
* [Django Rest Framework 3.14.0](https://www.django-rest-framework.org/)
* [Bootstrap 5.0](https://getbootstrap.com/)
* [VueJS 3.2.13](https://vuejs.org/)
* [AlpineJS](https://alpinejs.dev/)
* [htmx](https://htmx.org)
* [jQuery 3.4.1](https://jquery.com/)

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
