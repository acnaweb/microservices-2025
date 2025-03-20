# SOA - Microservices and Web Engineering

### [Apresentações](/apresentacao.md)
---
## Projetos

| Repositório | 
|----|
| [Repositório de conteúdos e acompanhamento de aulas](https://github.com/acnaweb/microservices-2025) |
| [Git](https://github.com/acnaweb/git) |
| [API](https://github.com/acnaweb/api) |
| [E-commerce](https://github.com/acnaweb/ecommerce) |
| [Turma 3SIR](https://github.com/acnaweb/study-apir) |
| [Turma 3ESW](https://github.com/acnaweb/study-apiw ) |
| [Turma 3ESX](https://github.com/acnaweb/study-apix ) |

### Toda aula :)

1 - Clonar seu (ou o meu) repositório:

```
git clone https://github.com/acnaweb/study-api.git
cd study-api
code  .
```

2 - Instalar extensão Java no VS Code

3 - Abrir Postman

4 - Logar no Github.com e obter token
```
Perfil > Settings
- Developer Settings
- PAT > Tokens (classic)
```
--- 
### Databases (Docker)

- https://github.com/acnaweb/database

--- 
### Maven 

- Executar a aplicação
  
```sh 
mvn spring-boot:run
```

--- 
### Criar aplicação Java Spring Boot        

- [Spring Initialzr](https://start.spring.io/) é utilizado para criar projetos com Sprint Boot

![Spring Initializr - Setup](/assets/img/spring_initializar_setup.png "Spring Initializr - Setup")

![Spring Initializr - Add Dependencies](/assets/img/spring_initializar_add_dependencies.png "Spring Initializr - Add Dependencies")

![Spring Initializr - Spring Web](/assets/img/spring_initializar_web_spring.png "Spring Initializr - Spring Web")


--- 

 
## Objetivos do Curso

- Desenvolver aplicação RESTful API
    - Spring Boot
    - Spring Data
    - Authorization/Authentication
    - Caching
    - Pagination and Sorting
    - Unit Test
    - OpenAPI - Swagger
    - Profiles: dev/stg/prd
- Docker: Container
- Deploy: Cloud Azure

### Extras

- GitHub: CI/CD
- API Gateway
- Event Driven: Kafka

### Metodologia

- Apresentação de conceito e implementação de forma interativa e cíclica.
- Criação de projetos no Github.
- Material disponível neste repositório.
- A cada aula o conteúdo é registrado neste repositório.

### Requisitos

- Github Account
- Azure Account (https://portal.azure.com/)
- Docker Hub Account
- Java 17
- Git
- Docker

### Plano de Estudo

- Conteinerização
    - [Docker](https://www.docker.com/)
    - [Docker/Playground](https://labs.play-with-docker.com/)
    - [Docker Hub](https://hub.docker.com/)

- Versionamento de Código
    - [Github](https://github.com/)
    - [Git Client](https://www.alura.com.br/conteudo/git-github-controle-de-versao--amp)
    - [Git](/conceitos/git.md)
    - [Git/Artigo](https://www.alura.com.br/artigos/comecando-com-git-aprendendo-versionar)
    - [Git/Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)
    - [Gitflow](https://www.atlassian.com/br/git/tutorials/comparing-workflows/gitflow-workflow)
    - [Markdown](https://dillinger.io/)

- [HTTP](https://developer.mozilla.org/pt-BR/docs/Web/HTTP)
    - [Status HTTP](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Status)
    - [Métodos HTTP](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods)
    - [Portas TCP/UDP](https://pt.wikipedia.org/wiki/Lista_de_portas_dos_protocolos_TCP_e_UDP)

- Persistencia
    - [Hibernate](https://hibernate.org/)
    - [H2 Database](https://www.h2database.com/html/main.html)
    - Oracle
    - [Oracle x Java: Type mapping](https://docs.oracle.com/cd/A97335_02/apps.102/a83724/basic3.htm)
    - [Spring profile/data.sql](https://www.baeldung.com/spring-boot-data-sql-and-schema-sql)
    - [Migration](https://www.baeldung.com/database-migrations-with-flyway)

- Software
    - [Spring Framework](/conceitos/spring.md)
    - [12Factors](https://github.com/acnaweb/12factors)
    - [Maven](/conceitos/maven.md)
    - [Design Patterns](https://www.tutorialspoint.com/design_pattern/index.htm)

- Spring
    - [Spring Initializr](https://start.spring.io/)
    - [spring-boot-devtools](https://www.baeldung.com/spring-boot-devtools)
    - [Spring profile](https://docs.spring.io/spring-boot/docs/1.2.0.M1/reference/html/boot-features-profiles.html)
    - [Spring Starters](https://docs.spring.io/spring-boot/docs/current/reference/html/using.html#using.build-systems.starters)

- MVC
    - [MVC](/conceitos/mvc.md)
    - Spring Boot MVC    
    - [Thymeleaf](https://www.thymeleaf.org/)
- Restful API
    - [API Rest](https://blog.betrybe.com/desenvolvimento-web/api-rest-tudo-sobre/)
    - [JSON Server](https://www.npmjs.com/package/json-server)
    - [JSON](https://www.json.org/json-en.html)
    - [Json Path](https://jsonpath.com/)
    - [Postman](https://www.postman.com/)
    - [Arquitetura de Microserviços](https://microservices.io/)
    - [Spring Boot API](https://spring.io/guides/tutorials/rest)    
    - Cache 
    - [DTO Pattern](https://www.baeldung.com/java-dto-pattern)
    - Mapeamento com ModelMapper
    - [Validação de DTO](https://www.javaguides.net/2021/04/spring-boot-dto-validation-example.html)
    - Paginação
    - [Handler Exception](https://www.baeldung.com/exception-handling-for-rest-with-spring)
    - [Swagger/Documentação](https://swagger.io/)

- Produtividade
    - [Lombok](https://projectlombok.org/)
    - 
- DevOps
    - [CI/CD](https://codefresh.io/learn/ci-cd/7-ci-cd-concepts-you-must-know/)
    - [Teste unitários](https://junit.org/junit5/)
    - [Github Actions](https://docs.github.com/pt/actions)

- Cloud
    - Azure
    - Azure Web App
      
- Java
    - [Java Method Reference](https://www.baeldung.com/java-method-references)         
    - [Data/hora calendar/simpledateformat](https://www.devmedia.com.br/trabalhando-com-as-classes-date-calendar-e-simpledateformat-em-java/27401)
    - [Data/hora date](https://www.w3schools.com/java/java_date.asp)
    - [Data/hora datetime](https://www.baeldung.com/java-8-date-time-intro)
      
- MVC
    - [MVC](/conceitos/mvc.md)
    - Spring Boot MVC        
      
### Cursos Alura

#### Java e Persistencia
- [jdbc-dao-persistenci](https://cursos.alura.com.br/course/jdbc-dao-persistencia)
- [java-jpa-consultas-avancadas-performance-modelos-complexo](https://cursos.alura.com.br/course/java-jpa-consultas-avancadas-performance-modelos-complexos)
- [servlets-fundamentos-programacao-web-jav](https://cursos.alura.com.br/course/servlets-fundamentos-programacao-web-java)
- [servlet-autenticacao-autorizacao-mvc](https://cursos.alura.com.br/course/servlet-autenticacao-autorizacao-mvc)

#### Microserviços
- [microsservicos-padroes-projeto](https://cursos.alura.com.br/course/microsservicos-padroes-projeto)
- [fundamentos-microsservicos-aprofundando-conceitos](https://cursos.alura.com.br/course/fundamentos-microsservicos-aprofundando-conceitos)
- [microsservicos-implementando-java-spring](https://cursos.alura.com.br/course/microsservicos-implementando-java-spring)
- [spring-boot-3-desenvolva-api-rest-java](https://cursos.alura.com.br/course/spring-boot-3-desenvolva-api-rest-java)
- [spring-boot-aplique-boas-praticas-proteja-api-rest](https://cursos.alura.com.br/course/spring-boot-aplique-boas-praticas-proteja-api-rest)
- [microservices-spring-cloud-service-registry-config-server](https://cursos.alura.com.br/course/microservices-spring-cloud-service-registry-config-server)
- [microsservicos-pratica-iac-cdk-deploy-aws](https://cursos.alura.com.br/course/microsservicos-pratica-iac-cdk-deploy-aws)

#### Transformação Digital
- [formacao-transformacao-digital](https://www.alura.com.br/formacao-transformacao-digital)

#### Docker
- [docker-criando-gerenciando-containers](https://alura.com.br/curso-online-docker-criando-gerenciando-containers)

### Links úteis

- [eBooks](https://www.kdnuggets.com/2015/09/free-data-science-books.html)

### [Sem categoria](/conceitos/sem_categoria.md)
