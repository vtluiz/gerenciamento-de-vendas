# gerenciamento-de-vendas

Este projeto é um sistema básico de gerenciamento de vendas que permite cadastrar clientes, produtos, realizar vendas, consultar e atualizar informações, bem como excluir dados. Ele utiliza um banco de dados SQL para gerenciar todas as informações.

## Estrutura do Banco de Dados

O banco de dados contém as seguintes tabelas:

- **Clientes**: Armazena as informações dos clientes, como nome, email e telefone.
- **Produtos**: Armazena os produtos disponíveis para venda, com informações sobre preço e estoque.
- **Vendas**: Armazena os registros das vendas realizadas, associando clientes e produtos.

## Scripts SQL

Os seguintes arquivos SQL estão disponíveis na pasta `src/`:

- **database.sql**: Contém a criação das tabelas `Clientes`, `Produtos` e `Vendas`, além da inserção de dados de exemplo.
- **consultas.sql**: Contém várias consultas úteis, como a visualização das vendas realizadas, produtos mais vendidos, e compras por cliente.
- **atualizacoes.sql**: Contém comandos para atualização de informações (estoque de produtos, dados de clientes) e exclusão de registros de vendas.

## Passos para Utilização

1. Clone este repositório.
2. Importe o arquivo `database.sql` em seu banco de dados MySQL ou MariaDB.
3. Execute as consultas no arquivo `consultas.sql` para gerar relatórios.
4. Utilize o arquivo `atualizacoes.sql` para manter o banco de dados atualizado.

## Requisitos

- MySQL ou MariaDB
- Acesso a um terminal SQL

## Licença

Este projeto está sob a licença MIT.
