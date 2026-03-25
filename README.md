# Django ORM - Gerenciamento de Clientes

Aplicação web desenvolvida com Django e MySQL para gerenciamento de clientes, endereços e dependentes.

## Tecnologias

- Python 3.13
- Django 5.1.5
- MySQL
- Bootstrap 4

## Funcionalidades

- Cadastro, edição e remoção de clientes
- Cadastro de endereços vinculados ao cliente
- Cadastro de dependentes
- Internacionalização (PT/EN)

## Como rodar localmente

1. Clone o repositório
2. Crie e ative o virtual environment
3. Instale as dependências: `pip install -r requirements.txt`
4. Configure o arquivo `.env` com suas credenciais
5. Rode as migrations: `python manage.py migrate`
6. Inicie o servidor: `python manage.py runserver`