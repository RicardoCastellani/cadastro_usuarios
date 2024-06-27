# Sistema de Cadastro com Django

Este projeto é um sistema de cadastro desenvolvido em Python utilizando o framework Django. Ele permite a criação e visualização de registros de usuários de forma segura e eficiente.

## Funcionalidades

- Cadastro de novos usuários num banco de dados
- Visualização de todos os usuários cadastrados

## Executando o Projeto Localmente

Para executar este projeto em seu ambiente local, siga as instruções abaixo:

### Requisitos

- Python
- Django

### Passos para Execução

1. Clone este repositório em seu computador:
   ```bash
   git clone https://github.com/RicardoCastellani/sistema_de_cadastro

2. Navegue até o diretório do projeto:
   ```bash
   cd sistema_de_cadastro

3. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt

4. Execute as migrações do Django para configurar o banco de dados:
   ```bash
   python manage.py migrate

5. Inicie o servidor de desenvolvimento:
   ```bash
   python manage.py runserver

6. Acesse o site em seu navegador através do endereço:
   ```bash
   http://localhost:8000/
