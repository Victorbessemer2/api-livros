📚 Sistema de Gerenciamento de Livros

Projeto desenvolvido para a disciplina de SW-II, com o objetivo de criar uma aplicação web para gerenciamento de livros.

A aplicação será desenvolvida utilizando FastAPI no back-end, MySQL para o banco de dados e HTML, CSS e JavaScript no front-end. O projeto será realizado em etapas durante as aulas e versionado no GitHub.

🎯 Objetivo

Desenvolver um sistema capaz de cadastrar, consultar, atualizar e excluir livros, utilizando uma API REST conectada a um banco de dados MySQL.

Cada livro terá as seguintes informações:

id — Identificador único do livro.
titulo — Título do livro.
autor — Autor do livro.
ano_publicacao — Ano em que o livro foi publicado.
disponivel — Indica se o livro está disponível.
🛠️ Tecnologias utilizadas
Python
FastAPI
Uvicorn
SQLAlchemy
PyMySQL
MySQL
XAMPP
phpMyAdmin
HTML
CSS
JavaScript
Visual Studio Code
Git e GitHub
🧩 Funcionalidades

O sistema contará com um CRUD completo:

Operação	Funcionalidade
🟢 Create	Cadastrar um novo livro
🔵 Read	Listar e consultar livros
🟠 Update	Atualizar informações de um livro
🔴 Delete	Excluir um livro

Além disso, a aplicação terá validação dos dados enviados e tratamento de erros HTTP.

🏗️ Desenvolvimento do projeto

O projeto será desenvolvido em quatro etapas, seguindo o cronograma definido para a atividade.

🟦 Etapa 1 — Fundação

Nesta primeira etapa será preparado o ambiente de desenvolvimento.

Será realizada:

Configuração do ambiente Python.
Instalação das dependências.
Criação do banco de dados biblioteca_db.
Configuração do MySQL pelo XAMPP.
Administração do banco utilizando o phpMyAdmin.
Configuração da conexão entre Python e MySQL.
Criação da rota de saúde da API.
🟩 Etapa 2 — Modelo e consultas

Na segunda etapa será iniciada a implementação do sistema de livros.

Será realizada:

Criação do modelo Livro.
Criação dos schemas.
Configuração da sessão do banco de dados.
Criação da rota POST para cadastrar livros.
Criação das rotas GET para consultar livros.
Realização de testes da API.
🟧 Etapa 3 — CRUD completo

Na terceira etapa serão adicionadas as operações restantes do CRUD.

Será realizada:

Implementação da rota PUT.
Implementação da rota DELETE.
Atualização de livros.
Exclusão de livros.
Validação dos dados.
Tratamento de erros HTTP.
Testes de todas as operações do CRUD.
🟥 Etapa 4 — Front End

Na última etapa será desenvolvida a interface que permitirá utilizar o sistema pelo navegador.

Será realizada:

Criação das páginas HTML.
Estilização utilizando CSS.
Implementação da lógica com JavaScript.
Consumo da API utilizando fetch.
Cadastro de livros pela interface.
Listagem dos livros.
Edição dos livros.
Exclusão dos livros.
Integração completa entre front-end, API e banco de dados.
🗄️ Banco de dados

O banco utilizado no projeto será o MySQL, executado através do XAMPP e administrado pelo phpMyAdmin.

O banco será chamado:

biblioteca_db


O arquivo de criação do banco será mantido no projeto:

database/biblioteca_db.sql


Esse arquivo será versionado no GitHub para possibilitar a reconstrução do banco de dados quando necessário.

O MySQL Workbench não será utilizado. Toda a administração do banco será feita pelo phpMyAdmin.

📁 Organização do projeto

A estrutura do projeto será organizada de acordo com o desenvolvimento das etapas. A estrutura final deverá conter arquivos semelhantes a:

projeto-livros/
│
├── database/
│   └── biblioteca_db.sql
│
├── app/
│   ├── __init__.py
│   ├── main.py
│   ├── database.py
│   ├── models.py
│   ├── schemas.py
│   └── rotas/
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── .env
├── .gitignore
├── requirements.txt
└── README.md


A estrutura poderá ser ajustada conforme o desenvolvimento do projeto em aula.

🔒 Variáveis de ambiente

As informações de acesso ao MySQL serão armazenadas em um arquivo .env.

Esse arquivo não será enviado para o GitHub, pois poderá conter a senha utilizada no banco de dados local.

O .gitignore será utilizado para impedir que informações privadas sejam publicadas.

🔄 Git e GitHub

O desenvolvimento será versionado utilizando Git e GitHub.

Ao final de cada etapa, serão realizadas as seguintes ações:

Conferência dos arquivos no VS Code.
Registro das alterações pelo painel Source Control.
Criação do commit correspondente à etapa.
Sincronização das alterações com o GitHub.

Os commits serão realizados conforme o cronograma da atividade, permitindo acompanhar a evolução do projeto.

📅 Cronograma
Etapa	Data — Turma 3F	Data — Turma 3C
🟦 Etapa 1	02/09/2026	03/09/2026
🟩 Etapa 2	09/09/2026	10/09/2026
🟧 Etapa 3	16/09/2026	17/09/2026
🟥 Etapa 4	23/09/2026	24/09/2026
🚀 Resultado esperado

Ao finalizar o projeto, será possível utilizar uma aplicação web completa para gerenciamento de livros.

O sistema terá:

API desenvolvida com FastAPI.
Banco de dados MySQL.
Conexão utilizando SQLAlchemy e PyMySQL.
CRUD completo.
Validação dos dados.
Tratamento de erros.
Interface web.
Comunicação entre front-end e API através do fetch.
Projeto versionado no GitHub.
📚 Disciplina

SW-II — 3º Bimestre

Projeto desenvolvido como atividade prática de desenvolvimento de uma aplicação web com API, banco de dados e interface gráfica.