# SOA - Microservices and Web Engineering

### [Apresentações](/apresentacao.md)
---
## Projetos

| Repositório | 
|----|
| [Repositório de conteúdos e acompanhamento de aulas](https://github.com/acnaweb/microservices-2025) |
| [Git](https://github.com/acnaweb/git) |
| [API](https://github.com/acnaweb/api) |
| [Tutorial Java API com Spring](https://github.com/acnaweb/java) |
| [Docker]([https://github.com/acnaweb/study-apix](https://github.com/acnaweb/docker) |
| [E-commerce](https://github.com/acnaweb/ecommerce) |
| [Turma 3SIR](https://github.com/acnaweb/study-apir) |
| [Turma 3ESW](https://github.com/acnaweb/study-apiw ) |
| [Turma 3ESX](https://github.com/acnaweb/study-apix ) |

### Toda aula :)

1 - Clonar seu (ou o meu) repositório:

```
git clone https://github.com/acnaweb/study-<api-turma>.git
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
5 - Docker

* Menu Iniciar (pesquisar por Docker)
  - Iniciar *Start Docker Service*
  - Clicar em *Docker Desktop*

6 - Subir MySQL

- https://hub.docker.com/_/mysql

```sh
docker run -d \
    --name mysql \
    --rm \
    -e MYSQL_ROOT_PASSWORD=root_pwd \
    -e MYSQL_USER=new_user \
    -e MYSQL_PASSWORD=my_pwd \
    -p 3306:3306 \
    mysql
```

--- 
### Guia de Markdown

- https://www.markdownguide.org/cheat-sheet/

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

## Apresentações

#### _Quem sou eu?_

- Antonio Carlos de Lima Júnior **(AC)**
- Bacharel em Ciência da Computação, MBA em Gestão de Negócios, Especialização em Estatística Aplicada e MBA em Digital Business
- 28 anos em TI, atualmente Gerente de Eng. e Arq. de Dados
- profantonio.junior@fiap.com.br / 11 99759-9276
- [Linkedin](https://www.linkedin.com/in/acnaweb/)

#### _Quem é você?_

- Nome
- Objetivos com relação ao curso
- Objetivos com relação a disciplina
- Qual seu momento em relação a estágio ou trabalho?

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

#### Formação Java Web
- https://cursos.alura.com.br/formacao-java-web-spring-boot

#### Transformação Digital
- [formacao-transformacao-digital](https://www.alura.com.br/formacao-transformacao-digital)

#### Docker
- [docker-criando-gerenciando-containers](https://alura.com.br/curso-online-docker-criando-gerenciando-containers)

### Links úteis

- [eBooks](https://www.kdnuggets.com/2015/09/free-data-science-books.html)

### [Sem categoria](/conceitos/sem_categoria.md)
