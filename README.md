# API REST - Controle da Loja Carvalho Store

API REST desenvolvida em Java com Spring Boot para o gerenciamento simples de clientes, produtos e pedidos de uma pequena loja, aplicando a arquitetura MVC e persistência com Spring Data JPA e MySQL.

## Tecnologias Utilizadas
* Java
* Spring Boot
* Spring Web
* Spring Data JPA
* MySQL
* Postman (testes de endpoints)

## Estrutura do Projeto
* `model`: Entidades JPA (`Cliente`, `Produto` e `Pedido`)
* `repository`: Interfaces de acesso a dados (`JpaRepository`)
* `controller`: Controladores REST com endpoints CRUD (`POST`, `GET`, `GET /{id}` e `DELETE /{id}`)

## Endpoints Principais
* **Clientes:** `/clientes`
* **Produtos:** `/produtos`
* **Pedidos:** `/pedidos`
