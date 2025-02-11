# RDBMS_SQL
Estudos sobre RDBMS - Relational Database Management System (RDBMS) e SQL - Structured Query Language - Linguagem de Consulta Estruturada.

Informações relevantes:

- Relational Database Management System (RDBMS): Sistema de Gerenciamento de Banco de Dados Relacional. É o software utilizado para criar, gerenciar e acessar bancos de dados relacionais. Exemplos populares incluem MySQL, PostgreSQL, Oracle e Microsoft SQL Server.
- SQL (Structured Query Language): Linguagem de Consulta Estruturada. É a linguagem padrão utilizada para interagir com bancos de dados relacionais, permitindo realizar operações como inserir, consultar, atualizar e excluir dados.

Em SQL, os comandos são categorizados em diferentes grupos, cada um com funções específicas para interagir com o banco de dados. Os principais tipos de comandos SQL são:

1. DDL (Data Definition Language - Linguagem de Definição de Dados)
Os comandos DDL são responsáveis por definir a estrutura do banco de dados, como criar, alterar e excluir tabelas, índices e outros objetos. Alguns exemplos de comandos DDL são:

CREATE: Cria um novo objeto no banco de dados (ex: CREATE TABLE, CREATE INDEX).
ALTER: Modifica a estrutura de um objeto existente (ex: ALTER TABLE, ALTER INDEX).
DROP: Exclui um objeto do banco de dados (ex: DROP TABLE, DROP INDEX).
TRUNCATE: Remove todos os dados de uma tabela, mas mantém sua estrutura.
2. DML (Data Manipulation Language - Linguagem de Manipulação de Dados)
Os comandos DML são utilizados para manipular os dados dentro das tabelas, como inserir, atualizar e excluir registros. Alguns exemplos de comandos DML são:

INSERT: Insere novos registros em uma tabela.
UPDATE: Atualiza registros existentes em uma tabela.
DELETE: Exclui registros de uma tabela.
3. DQL (Data Query Language - Linguagem de Consulta de Dados)
O comando DQL mais importante é o SELECT, que permite consultar e recuperar dados de uma ou mais tabelas. É possível usar filtros, ordenação e outras cláusulas para refinar a consulta e obter os resultados desejados.

SELECT: Consulta e recupera dados de uma ou mais tabelas.
4. DCL (Data Control Language - Linguagem de Controle de Dados)
Os comandos DCL são responsáveis por controlar o acesso e as permissões dos usuários no banco de dados, como conceder e revogar privilégios. Alguns exemplos de comandos DCL são:

GRANT: Concede permissões a usuários.
REVOKE: Revoga permissões de usuários.
5. TCL (Transaction Control Language - Linguagem de Controle de Transações)
Os comandos TCL são utilizados para gerenciar as transações no banco de dados, como iniciar, confirmar (commit) ou cancelar (rollback) as operações. Alguns exemplos de comandos TCL são:

BEGIN: Inicia uma nova transação.
COMMIT: Confirma as alterações feitas na transação.
ROLLBACK: Cancela as alterações feitas na transação.
