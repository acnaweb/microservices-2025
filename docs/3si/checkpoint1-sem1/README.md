# SOA - Microservices and Web Engineering  

## Check Point 1/1º semestre/2025 - Prof. Antonio Carlos de Lima Júnior  

### Atividades  

#### Modelo Entidade Relacionamento

![](out/docs/3es/checkpoint1-sem1/agenda/diagram.png)

#### 1. (1 ponto) - Criar um projeto Java usando Spring Boot:  

- Project: Maven Project  
- Language: Java  
- Spring Boot: 3.4.*  
- Project Metadata:  
  - Group: br.com.fiap  
  - Artifact: checkpoint1  
  - Name: checkpoint1  
  - Description: Checkpoint 1  
  - Package Name: br.com.fiap.checkpoint1  
  - Packaging: Jar  
  - Java: 17/18  
- Dependências:  
  - Spring Web  
  - Spring DevTools  
  - Documentação Swagger - https://springdoc.org/  

#### 2. (1 ponto) - Criar o projeto.

Utilizar o [Spring Initializr](https://start.spring.io/) para criação do projeto.

#### 3. (2 pontos) - Criar a documentação para o repositório.

Utilizar o README.md de https://github.com/acnaweb/study-apir/blob/feature/uc-service-crud/README.md como base.



3. (2 pontos) - Implementar um endpoint GET /ping  
- Ao consumir o endpoint /ping a aplicação deverá retornar "pong"  

4. (3 pontos) - Criar o respectivo Dockerfile  
O Dockerfile deverá conter as instruções para compilação e execução da aplicação.  

FROM maven:3.8.7-openjdk-18-slim AS build  
RUN mkdir /opt/app  
COPY . /opt/app  
WORKDIR /opt/app  
RUN mvn clean package  

FROM eclipse-temurin:18-jre-alpine  
RUN mkdir /opt/app  
COPY --from=build /opt/app/target/app.jar /opt/app/app.jar  
WORKDIR /opt/app  
ENV PROFILE=dev  
EXPOSE 8080  
ENTRYPOINT ["java", "-jar", "app.jar"]  

5. (2 pontos) - Imagem no Docker Hub  
- Upload da imagem no Docker Hub do respectivo membro.  
- Nome do repositório: fiap-checkpoint1  
- Tag: latest  

Entregáveis  

1. GitHub (para cada membro)  
   - Nome do repositório: fiap-checkpoint1-sem1  

2. Docker Hub (para cada membro)  
   - Nome do repositório: fiap-checkpoint1-sem1  

3. Arquivo para área de entrega de trabalhos  
   - Arquivo txt contendo as seguintes informações no exemplo abaixo:  

Aluno(a)      Github  
Maria         https://github.com/maria/fiap-checkpoint1-sem1  
João          https://github.com/joao/fiap-checkpoint1-sem1  

Links úteis:  
- https://springdoc.org/  
- https://start.spring.io/  
- https://github.com/maria/fiap-checkpoint1-sem1  
- https://github.com/joao/fiap-checkpoint1-sem1  
