# 🛒 New Jeans - Loja E-commerce 
---
## Descrição

**New Jeans** é uma aplicação de e-commerce de roupas que permite aos usuários cadastrar-se, fazer login, visualizar e comprar produtos. O projeto também possui funcionalidades completas de carrinho de compras, incluindo a inserção, visualização, alteração, remoção de produtos e finalização de compra. A aplicação integra-se com um banco de dados MySQL para o armazenamento dos dados dos usuários e produtos no carrinho de compras.

## ⚙ Funcionalidades

- **Cadastro de Usuário:** Permite que novos usuários se cadastrem na plataforma.
- **Login e Logout:** Autenticação dos usuários cadastrados.
- **Visualização de Produtos:** Exibe uma lista de produtos disponíveis para compra.
- **Compra de Produtos:** Permite que usuários adicionem produtos ao carrinho de compras.
- **Carrinho de Compras:**
  - **Visualizar Produtos:** Exibe todos os produtos presentes no carrinho.
  - **Alterar Produtos:** Permite modificar a quantidade de produtos no carrinho.
  - **Remover Produtos:** Remove produtos do carrinho.
  - **Finalizar Compra:** Processa a compra dos produtos presentes no carrinho, apenas para clientes logados no site.

## 💻 Tecnologias Utilizadas

- **IDE:** Visual Studio Code
- **Linguagens de Programação:** 
  - HTML
  - CSS
  - PHP
  - SQL
- **Banco de Dados:** MySQL
- **Framework**: Bootstrap


## 📌 Pré-requisitos

- **Servidor Web:** XAMPP, ou outro servidor compatível com PHP e MySQL.
- **MySQL:** Para gerenciamento do banco de dados.
- **Navegador:** Para acessar a aplicação web.

## 🕹 Como Executar

1 - **Clone o repositório:**
   ```bash
   git clone https://github.com/nolascolunardi/New_Jeans_Loja.git
   ```
2 - **Instale o [XAMPP](https://www.apachefriends.org/index.html):**
  
3 - **Inicie o servidor Apache e MySQL.**

4 - **Configure o banco de dados:**
   - Abra o phpMyAdmin e crie um novo banco de dados chamado `newjeans`.
   - Escreva os comandos do arquivo `newjeans_db.txt` localizado no diretório `db` para criar as tabelas do banco de dados.

5 - **Configure o arquivo de conexão do banco de dados:**
   - No arquivo `conexao.php`, ajuste as credenciais do MySQL conforme necessário:
     ```php
     <?php
        $conexao = new mysqli('localhost', 'usuario', 'senha', 'newjeans') 
        or die("Erro de conexão: ".$conexao -> connect_error);    
      ?>
     ```

6 - **Inicie a aplicação:**
   - Mova os arquivos do projeto para o diretório `htdocs` do XAMPP.
   - Abra o navegador e acesse `http://localhost/newjeans/index.php`.


## ✍ Autores
- [@Ana Laura Nolasco Lunardi](https://github.com/analunardi)
- [@Leonardo Vinicius](https://github.com/leonardovinicius)
