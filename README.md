# 📅 Criar Eventos

Este projeto é uma aplicação web simples para **cadastro, edição e exclusão de eventos**, desenvolvida com foco educacional utilizando tecnologias básicas como PHP, HTML, CSS e JavaScript.

## 🚀 Funcionalidades

- ✅ Criar eventos com nome, data, descrição e localização.
- 📋 Listar todos os eventos cadastrados.
- ✏️ Editar eventos existentes.
- ❌ Excluir eventos.

## 🛠 Tecnologias Utilizadas

- PHP (com PDO para banco MySQL)
- HTML5
- CSS3
- JavaScript
- MySQL

## 💻 Como rodar o projeto localmente

1. Clone o repositório:

```bash
git clone https://github.com/Luidcasotti/criar-eventos.git
Crie um banco de dados chamado eventos no seu MySQL.

Importe o arquivo SQL (se existir) da pasta config/.

Altere os dados de conexão no arquivo config/connection.php com seu host, usuário e senha.

Inicie seu servidor (XAMPP, WAMP, Laragon etc.) e acesse:
http://localhost/criar-eventos/public/

📁 Estrutura do Projeto
criar-eventos/
├── config/          # Contém arquivos de configuração, incluindo conexão com o banco
│   └── db_connect.php
├── public/          # Contém os arquivos de frontend e scripts principais
│   ├── css/
│       └── estilo.css
│   ├── evento/
│       ├── criar.php
│       ├── editar.php
│       ├── excluir.php
│       └── listar.php
│   ├── js/
│       └── administrador.js
│   └── administrador.html
├── index.php        # Redireciona para a pasta public
└── README.md


🤝 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.
