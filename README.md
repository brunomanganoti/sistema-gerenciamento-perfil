# Sistema de Gerenciamento de Perfil

Projeto acadêmico desenvolvido na disciplina de Programação de Sistemas Web.

## 📌 Descrição

Este projeto é um sistema web básico em PHP para gerenciamento de perfis de usuários, incluindo funcionalidades como:

- Cadastro de usuário
- Login e Logout
- Atualização de perfil
- Comentários
- Consulta e exclusão de registros

## 🧰 Tecnologias Utilizadas

- PHP  
- HTML  
- CSS  
- MySQL  

## 📁 Estrutura do Projeto

Arquivos principais do sistema:

- `login.html` – Formulário de login  
- `registro.php` – Cadastro de usuários  
- `acesso.php` / `proc_Login.php` – Lógica de autenticação  
- `att-perfil.html` / `proc_Attperfil.php` – Atualização de perfil  
- `comentario.html` / `proc_Comentario.php` – Sistema de comentários  
- `consultar.php` – Consulta de usuários  
- `excluir.php` – Exclusão de usuários  
- `sair.php` – Logout  
- `conexao.php` – Conexão com o banco de dados  
- `estilosgp.css` – Estilos CSS  

## 🚀 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/brunomanganoti/sistema-gerenciamento-perfil.git
   ```
2. Coloque os arquivos em um servidor local (XAMPP, WAMP).
3. Configure o banco de dados MySQL e ajuste as credenciais no arquivo `conexao.php`.
4. Acesse no navegador:
   ```
   http://localhost/sistema-gerenciamento-perfil/
   ```
