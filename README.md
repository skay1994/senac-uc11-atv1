# Sistema de Leilões (Senac UC11)

## Nome do projeto
**Sistema de Leilões** — projeto da Unidade Curricular 11 (UC11).

## Sobre o projeto
Aplicação desktop desenvolvida em Java (Swing) para o gerenciamento de um sistema
de leilões. O sistema permite cadastrar produtos que serão leiloados, informando
nome e valor, e consultar a listagem dos produtos cadastrados. Os dados são
persistidos em um banco de dados MySQL, por meio das classes DAO
(`conectaDAO` e `ProdutosDAO`).

Principais telas/classes:
- `cadastroVIEW` — tela de cadastro de produtos (nome e valor).
- `listagemVIEW` — tela de consulta/listagem dos produtos.
- `ProdutosDTO` — objeto de transferência de dados do produto.
- `ProdutosDAO` / `conectaDAO` — acesso ao banco de dados MySQL.

## Tecnologias utilizadas
- **Java** (Java SE, Swing / NetBeans)
- **MySQL** (banco de dados `uc11`, script `uc11.sql`)
- **JDBC** (MySQL Connector/J — `mysql-connector-java`)
- **Git / GitHub** (versionamento de código)
