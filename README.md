# Projeto Agenda Django

![127 0 0 1_8000_](https://github.com/EricW900/projeto-agenda-django/assets/113937150/e03248d2-234f-4b29-aa06-590916e2560d)

## Descrição

Este é um projeto de estudo desenvolvido com o objetivo de criar uma agenda utilizando Django. A aplicação permite a realização de operações CRUD (Create, Read, Update, Delete), além de contar com funcionalidades de sessão, como login e logout, e um painel administrativo intuitivo fornecido pelo próprio Django.

## Funcionalidades

- **Cadastro de Contas:** Usuários podem se cadastrar e criar suas próprias contas.
- **Login e Logout:** Sistema de autenticação para acesso seguro.
- **CRUD de Eventos:** Adição, visualização, edição e exclusão de eventos.
- **Painel Administrativo:** Interface administrativa padrão do Django para gerenciamento avançado.
- **Banco de Dados SQLite:** Utilização do banco de dados SQLite para armazenamento dos dados.
- **Frontend:** Interface web criada com HTML e CSS.

## Tecnologias Utilizadas

- **Python**
- **Django**
- **HTML**
- **CSS**
- **SQLite**

## Como Executar o Projeto

### Pré-requisitos

- Python 3.12.4 instalado (Versões anteriores podem funcionar)
- Pip (gerenciador de pacotes do Python)

### Passos para executar

1. **Clone o repositório:**

    ```bash
    git clone https://github.com/EricW900/projeto-agenda-django.git
    ```

2. **Acesse o diretório do projeto:**

    ```bash
    cd projeto-agenda-django
    ```

3. **Crie um ambiente virtual:**

    ```bash
    python -m venv venv
    ```

4. **Ative o ambiente virtual:**

    - No Windows:

        ```bash
        venv\Scripts\activate
        ```

    - No macOS/Linux:

        ```bash
        source venv/bin/activate
        ```

5. **Instale as dependências:**

    ```bash
    pip install -r requirements.txt
    ```

6. **Realize as migrações do banco de dados:**

    ```bash
    python manage.py migrate
    ```

7. **Inicie o servidor:**

    ```bash
    python manage.py runserver
    ```

8. **Acesse a aplicação no navegador:**

    Abra seu navegador e vá até a URL:

    ```
    http://127.0.0.1:8000
    ```

### Recomendações

- **Banco de Dados:** Utilize o DBeaver para visualizar e gerenciar o banco de dados SQLite utilizado na aplicação.

## Imagens do Projeto
### Tela de Login
![127 0 0 1_8000_user_login_](https://github.com/EricW900/projeto-agenda-django/assets/113937150/136275bb-3e97-4e98-8515-8756bcdb34a7)

## Tela de detalhes do Contato
![127 0 0 1_8000_contact_2291_detail_](https://github.com/EricW900/projeto-agenda-django/assets/113937150/d17dd53a-71cb-4ed2-bb30-fbb4768266c8)

## Tela de Cadastro de Contato
![127 0 0 1_8000_contact_create_](https://github.com/EricW900/projeto-agenda-django/assets/113937150/76f3b78c-ae8d-47c8-b8e3-d6ce4529b0f9)



## Agradecimentos

Gostaria de agradecer imensamente ao professor Otávio Miranda do curso de Python na Udemy por todo o suporte e ensinamentos que tornaram este projeto possível.
