# Beer API
API para gerenciamento de cervejas, criada através do curso online da [Digital Innovation One](https://digitalinnovation.one/)

[Desenvolvimento de testes unitários para validar uma API REST de gerenciamento estoques de cerveja](https://gft.digitalinnovation.one/project/desenvolvimento-de-testes-unitarios-para-validar-uma-api-rest-de-gerenciamento-estoques-de-cerveja/learning/d00f891f-65bb-4149-85f0-57d771116214?back=/track/java-developer-1)

Criado a partir do projeto [beer_api_digital_innovation_one](https://github.com/vagnerpgss/beer_api_digital_innovation_one)

## Requisitos
* [java] 11
* [maven] 3.6.3
* [Spring Boot] 2.4.4
* [JUnit] 5
* [Mockito]
* [Hamcrest]
* [Intellij IDEA]
* [docker] - em breve
* [docker-compose] - em breve

## Rodando a aplicação
Para executar o projeto no terminal, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

## Testes
Para executar a suíte de testes desenvolvida durante a live coding, basta executar o seguinte comando:

```shell script
mvn clean test
```

## Docker
TODO - Dockerizar a aplicação

## Documentação da API
Documentação através do [Swagger 2](http://localhost:8080/beers-api/swagger-ui/#/).

## Postman
Collection do Postman na pasta /postman

## URL do Projeto
Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/beers-api/api/v1/beers
```

## URLs Úteis

* [Referência do Intellij IDEA Community, para download](https://www.jetbrains.com/idea/download)
* [Palheta de atalhos de comandos do Intellij](https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf)
* [Site oficial do Spring](https://spring.io/)
* [Site oficial JUnit 5](https://junit.org/junit5/docs/current/user-guide/)
* [Site oficial Mockito](https://site.mockito.org/)
* [Site oficial Hamcrest](http://hamcrest.org/JavaHamcrest/)
* [Referências - testes em geral com o Spring Boot](https://www.baeldung.com/spring-boot-testing)
* [Referência para o padrão arquitetural REST](https://restfulapi.net/)
* [Referência pirâmide de testes - Martin Fowler](https://martinfowler.com/articles/practical-test-pyramid.html#TheImportanceOftestAutomation)
