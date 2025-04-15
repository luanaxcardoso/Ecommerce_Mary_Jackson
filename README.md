<h2 style="text-align: center;">Bootcamp Python & Django - 🦋 WoMakers Code 🦋</h2>

### 💻 E-commerce Mary Jackson

Este é o projeto final do Bootcamp de Back-End que tem por objetivo consolidar e aplicar o conhecimento adquirido Python e o Framework Django.

#### Linguagens e Ferramentas utilizadas:

<div>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" style="border-radius:4px"/>
<img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" style="border-radius:4px"/>
<img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white"/>
<img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" style="border-radius:4px"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" style="border-radius:4px"/>
</div>

## O projeto foi realizado pela Squad Mary Jackson:

### 📄 Estrutura e Requisitos

#### 1. Especificações Técnicas

- **Ambiente de Desenvolvimento**: Configurar um ambiente virtual Django local.
- **Controle de Versão com Git**: Criar um repositório no GitHub e manter um registro claro de todas as alterações no projeto, permitindo o acompanhamento do progresso.
- **Design Responsivo**: Desenvolver um design responsivo utilizando HTML5, CSS3 e Bootstrap, garantindo que o e-commerce seja acessível e funcional em dispositivos móveis.
- **Banco de Dados**: Configurar um banco de dados SQLite ou PostgreSQL para armazenar as informações do e-commerce.
- **Modelos Django**: Definir modelos Django que representem produtos, categorias, pedidos e informações de pagamento.

#### 2. Funcionalidades do E-commerce

- **Catálogo de Produtos**: Criar uma seção de catálogo de produtos, incluindo imagens, preços e descrições.
- **Páginas de Detalhes**: Implementar páginas de detalhes para visualização individual do produto, com informações como descrição, imagens e outras características relevantes.
- **Carrinho de Compras**: Desenvolver um sistema de carrinho de compras que permita aos usuários adicionar, remover e atualizar produtos no carrinho.
- **Barra de Busca**: Implementar uma barra de pesquisa que permita aos usuários procurar produtos por palavras-chave, facilitando a navegação no e-commerce.
- **Sistema de Autenticação**: Criar um sistema de autenticação de usuários, permitindo que os clientes se registrem, façam login e gerenciem suas contas.
- **Gestão de Pedidos**: Permitir que os clientes façam pedidos e possam visualizar detalhes do pedido.

#### 4. Administração do Django

- **Interface de Administração**: Utilizar a interface de administração do Django para gerenciar produtos, categorias, pedidos e clientes.
- **Gerenciamento de Produtos**: Permitir que os administradores adicionem, editem e removam produtos do catálogo.
- **Gerenciamento de Pedidos**: Permitir que os administradores visualizem e gerenciem os pedidos feitos pelos clientes.
- **Gerenciamento de Clientes**: Permitir que os administradores visualizem e gerenciem as contas dos clientes.
- **Gerenciamento de Categorias**: Permitir que os administradores adicionem, editem e removam categorias de produtos.
- **Gerenciamento de Estoque**: Permitir que os administradores visualizem e gerenciem o estoque dos produtos.


#### 5. Deploy

- O projeto foi publicado utilizando o **PythonAnywhere**.

### 💻 Como Rodar o Projeto na Sua Máquina

Ao entrar no projeto pela primeira vez, siga os passos abaixo:

1. **Instalação do virtualenv** (caso não tenha o virtualenv instalado):

   ```bash
   pip install virtualenv
    ```

2. **Criação do ambiente virtual**:
     
    ```bash
    py -m venv .venv ou python -m venv .venv
    ```

3. **Ativação do ambiente virtual**: 

    ```bash
    .\.venv\Scripts\activate
    ```

4. **Instalação dos requisitos**: 
        
    ```bash
    pip install -r requirements.txt 
    ```

5. **Atualização do banco de dados**:
    
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

6. **Criação de um superusuário**:

    ```bash
    python manage.py createsuperuser
    ```

7. **Rodar o servidor**:

    ```bash
    python manage.py runserver
    ```
- E acesse o site no endereço:
http://127.0.0.1:8000/

8. **Rodar os testes**:

    ```bash
    python manage.py test app_MJ
    ```

-------------------------------------------------------------------------------------------------------

- **Atualização do requirements.txt** (após cada nova instalação de dependência):

    ```bash
    pip freeze > requirements.txt
    ```

