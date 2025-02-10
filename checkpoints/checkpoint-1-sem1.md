# Microservice and Web Engineering - 3SIT/2024

## Check Point 1/1º semestre - Prof. Antonio Carlos de Lima Júnior

### Instruções Gerais

- Prazo de entrega: __15/03__.
- O checkpoint deverá ser desenvolvido em até 3 pessoas.
- Cada membro deve ter o projeto em seu próprio repositório no Github até a data de entrega.

### Atividades

#### 1. (_1 ponto_) - Criar um projeto Java usando Spring Boot:

> - Project: 		Maven Project
> - Language: 	Java
> - Spring Boot: 	3.1.*

Project Metadata

> - Group: 	br.com.fiap
> - Artifact: 	checkpoint1
> - Name: 	checkpoint1
> - Description: Checkpoint 1
> - Package Name: br.com.fiap.checkpoint1
> - Packaging: 	Jar
> - Java: 		17

Dependencias

> - Spring Web

#### 2. (_1 ponto_) - Adicionar 3 Spring profiles: 

> * dev - porta 8080
> * stg - porta 8080
> * prd - porta 8080

#### 3. (_2 pontos_) - Implementar um endpoint GET ping.

Ao consumir o endpoint __/ping__ a aplicação deverá retornar:
> - profile "dev" -> "Pong em dev" 
> - profile "stg" -> "Pong em stg" 
> - profile "prd" -> "Pong em prd" 

#### 4. (_3 pontos_) - Criar o respectivo Dockerfile

O Dockerfile deverá conster as instruções para compilação e excução da aplicação.

#### 5. (_2 pontos_) -  Imagem no Docker Hub 

Upload da imagem do docker hub do respectivo membro

> - nome do repositório: fiap-checkpoint1
> - tag: latest

#### 6. (_1 ponto_) - Adicionar instruções no README.md do respostório

> - Comando "docker" para executar a aplicação a partir do docker hub do __respectivo membro__ com profile "dev"
> - Comando "docker" para executar a aplicação a partir do docker hub do __respectivo membro__ com profile "stg"
> - Comando "docker" para executar a aplicação a partir do docker hub do __respectivo membro__ com profile "prd"


### Entregáveis

#### 1. Github (para cada membro)

Nome do repositorio: __fiap-checkpoint1__

#### 2. Docker hub (para cada membro)

Nome do repositorio: __fiap-checkpoint1__

#### 3. Arquivo para área de entrega de trabalhos

Arquivo txt contendo as seguintes informações no exemplo abaixo:

| Aluno(a) | Github |
| --- | --- |
| Maria | https://github.com/maria/fiap-checkpoint1 |
| João | https://github.com/joao/fiap-checkpoint1 |
| Ana | https://github.com/ana/fiap-checkpoint1 |


