# BACKend - Meeting-Room
* O back-end do projeto consistiu na construção de uma API com Spring Boot para gerenciar determinada lista de salas de reunião e utilizou-se o Spring Data para persistência de dados e o banco in-memory H2; tal back-end com o auxílio dos conceitos da linguagem Java.

### Digite o seguinte comando para executar o projeto no terminal:

```shell script
mvn spring-boot:run 
```

## Tech Stacks:
 * Spring Web
 * Spring Data JPA
 * H2 Database
 * Java 8
 * Maven
 
## Endpoints criados na API

* Criar sala de reunião sem especificar ID
POST - /api/v1/rooms

* Listar todas as salas
GET - /api/v1/rooms

* Buscar uma sala pelo Id
GET - /api/v1/rooms/{id}

* Atualizar uma sala pelo Id
PUT - /api/v1/rooms/{id}

* Excluir uma sala pelo Id
DELETE - /api/v1/rooms/{id}
