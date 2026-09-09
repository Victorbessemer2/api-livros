📚 Sistema de Gerenciamento de Livros

Projeto desenvolvido para a disciplina SW-II — 3º Bimestre. O objetivo é criar um sistema web para gerenciamento de livros, permitindo cadastrar, consultar, editar e excluir registros.

🎯 Objetivo

O sistema terá um CRUD completo de livros com os seguintes dados:

id
titulo
autor
ano_publicacao
disponivel
🛠️ Tecnologias
Python
FastAPI
SQLAlchemy
PyMySQL
MySQL
XAMPP
phpMyAdmin
HTML, CSS e JavaScript
Git e GitHub
🧩 Funcionalidades
🟢 Cadastrar livros
🔵 Listar e consultar livros
🟠 Editar livros
🔴 Excluir livros
✅ Validar dados
⚠️ Tratar erros da API
🏗️ Etapas
🟦 Etapa 1 — Fundação

Configuração do ambiente, MySQL, banco biblioteca_db, conexão com o Python e criação da API inicial.

🟩 Etapa 2 — Modelo e consultas

Criação do modelo Livro, schemas e rotas POST e GET.

🟧 Etapa 3 — CRUD

Implementação das rotas PUT e DELETE, validações e tratamento de erros.

🟥 Etapa 4 — Front-end

Criação da interface com HTML, CSS e JavaScript e integração com a API usando fetch().

🗄️ Banco de dados

O banco será MySQL, executado pelo XAMPP e administrado pelo phpMyAdmin.

biblioteca_db


O script ficará em:

database/biblioteca_db.sql

📁 Estrutura
projeto-livros/
├── database/
│   └── biblioteca_db.sql
├── app/
│   ├── main.py
│   ├── database.py
│   ├── models.py
│   ├── schemas.py
│   └── rotas/
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
├── .env
├── .gitignore
├── requirements.txt
└── README.md

🔄 Git e GitHub

O projeto será versionado com Git e enviado ao GitHub ao final de cada etapa.

📅 Cronograma
Etapa	3F	3C
🟦 1	02/09/2026	03/09/2026
🟩 2	09/09/2026	10/09/2026
🟧 3	16/09/2026	17/09/2026
🟥 4	23/09/2026	24/09/2026
🚀 Resultado

Ao final, teremos uma aplicação web completa para gerenciamento de livros, integrada entre front-end, API e banco de dados.

Disciplina: SW-II — 3º Bimestre