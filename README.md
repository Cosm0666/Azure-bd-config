# Etapas para criar uma intancia de banco de dados
## 1. Acessar portal azure
  - fazer login na conta Microsoft

## 2. Criar um gupo de recursos
  O grupo de recursos funciona como um container para armazenar recursos relacionados

### Passos:
  1. Pesquisar por "resource group"
  2. Selecionar Criar
  3. Informar
     - assinatura
     - Nome do grupo
     - regiao

## 3. Criar banco de dados
Opçoes de db
  - Azure SQL Database
  - Azure Database for MySQL
  - Azure Database for PostgreSQL
  - Azure Cosmos DB
### Exemplo utilizando Azure SQL Database
  1. Pesquisar por "SQL Database".
  2. Selecionar Create.
  3. Configurar:
      - Nome do banco.
      - Servidor SQL.
      - Usuário administrador.
      - Senha.
      - Região.
      - Modelo de computação.
    
## 4. Configurar Rede e Segurança
### Firewall
  - Adicionar o IP local para permitir conexões externas.

### Autenticação:
  - Usuário e senha.
  - Integração com Azure Active Directory.

## 5. Revisar e Implantar
Após revisar as configurações:
  - Clicar em Review + Create.
  - Validar os parâmetros.
  - Selecionar Create.

O Azure iniciará a implantação automaticamente.
