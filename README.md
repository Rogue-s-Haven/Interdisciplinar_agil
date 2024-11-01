---------------------------------------------------Front--------------------------------------------------------------
#
---------------------------------------------------Front--------------------------------------------------------------
#
---------------------------------------------------Backend------------------------------------------------------------

Este projeto é uma API construída usando **Java, Java Spring, Migrações Flyway, PostgresSQL como banco de dados, e Spring Security e JWT para controle de autenticação.**

## Instalação

1. Instale as dependências com o Maven.
2. Instale o [PostgresSQL](https://www.postgresql.org/).

## Uso

1. Inicie a aplicação com o Maven.
2. A API estará acessível em http://localhost:8080.

## Endpoints da API
A API fornece os seguintes endpoints:

```markdown
GET /product - Recupera uma lista de todos os produtos. (todos os usuários autenticados)

POST /product - Registra um novo produto (acesso ADMIN requerido).

POST /auth/login - Realiza login no aplicativo.

POST /auth/register - Registra um novo usuário no aplicativo.
```

## Autenticação
A API utiliza o Spring Security para controle de autenticação. As seguintes funções estão disponíveis:

```
USER -> Função padrão para usuários logados.
ADMIN -> Função de administrador para gerenciar parceiros (registrar novos parceiros).
```
## Banco de Dados
O projeto utiliza o [PostgresSQL](https://www.postgresql.org/) como banco de dados.
#

---------------------------------------------------Backend------------------------------------------------------------
