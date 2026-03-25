# 🚀 Parking Spot API

A Parking Spot API é uma API REST simples para gerenciamento de vagas de veiculos para apartamentos.

O projeto permite realizar operações básicas de CRUD:

✅ Criar

✅ Listar

✅ Buscar por ID

✅ Atualizar por ID

✅ Remover por ID

Os métodos possuem validação para que seja seguido o modelo de dados a serem salvos.

A listagem de itens possue paginação.

A API foi desenvolvida utilizando:

Springboot, Java 17, Hibernate ORM com Panache, PostgreSQL, Swagger / OpenAPI e Lombok.

O objetivo do projeto é demonstrar a construção de uma API REST utilizando boas práticas de desenvolvimento com Springboot.


## Subindo a aplicação no modo dev

Você pode executar sua aplicação em modo de desenvolvimento, que permite recarga automática (live coding), usando:

```shell script
./mvnw springboot:dev
```
## Guias de Extensões Relacionadas

- REST com Jackson ([guia](https://quarkus.io/guides/rest)): Implementação moderna de Jakarta REST no Quarkus, com processamento em tempo de build e integração com Jackson para conversão automática entre objetos Java e JSON.
- JDBC Driver - PostgreSQL ([guia](https://quarkus.io/guides/datasource)): Permite conectar ao banco de dados PostgreSQL utilizando JDBC, com suporte a pool de conexões e integração com o Hibernate ORM.
- Hibernate ORM com Panache ([guia](https://quarkus.io/guides/hibernate-orm-panache)): Simplifica o código de persistência usando Hibernate ORM, através do padrão Active Record ou Repository Pattern.
- OpenAPI / Swagger (SmallRye OpenAPI) ([guia](https://quarkus.io/extensions/io.quarkus/quarkus-smallrye-openapi/)): Gera automaticamente a documentação da API REST e disponibiliza a interface Swagger UI para testes interativos dos endpoints.

## Dúvidas

- Não consegui seguir o modelo da config utilizada pela professora para formatação de data. Acabou que não tive o mesmo resultado que ela.
- Explicar o @Bean e BeanUtils