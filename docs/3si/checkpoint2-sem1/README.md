# SOA - Microservices and Web Engineering  

## Check Point 2/1º semestre/2025 - Prof. Antonio Carlos de Lima Júnior  

### Instruções Gerais

- Atividade a ser desenvolvida em 1 ou 2 pessoas.
- Entrega individual.
- Observe o Modelo Entidade Relacionamento (MER) e siga as instruções a partir do item 1.

   ![](\out\docs\3si\checkpoint2-sem1\mer\diagram.png)

Criar projeto Java usando Spring Boot:  

### Projeto 

Utilizar o [Spring Initializr](https://start.spring.io/) para criação do projeto.

- Project: Maven Project  
- Language: Java  
- Spring Boot: 3.4.*  
- Project Metadata:  
  - Group: br.com.fiap  
  - Artifact: checkpoint2  
  - Name: checkpoint2  
  - Description: Checkpoint 2  
  - Package Name: br.com.fiap.checkpoint2  
  - Packaging: Jar  
  - Java: 17/18  
- Dependências:  
  - Spring Web  
  - Spring DevTools  
  - Documentação Swagger - https://springdoc.org/ 

### Rotas (endpoints)

   * POST /pacientes
   * GET /pacientes
   * GET /pacientes/{id}
   * PUT /pacientes/{id}
   * DELETE /pacientes/{id}

   * POST /profissionais
   * GET /profissionais
   * GET /profissionais/{id}
   * PUT /profissionais/{id}
   * DELETE /profissionais/{id}   

   * POST /consultas
   * GET /consultas
   * GET /consultas/{id}
   * PUT /consultas/{id}
   * DELETE /consultas/{id} 
  
### Atividades 

#### 1. (4 pontos) - Implementar as controllers com base nas rotas e MER.

#### 2. (4 pontos) - Implementar os DTOs com base nas rotas e MER.

#### 3. (2 pontos) - Modelas as entidades conforme o MER.

Utilizar o README.md de https://github.com/acnaweb/study-apir/blob/feature/uc-service-crud/README.md como base.

### Instruções de Entrega  

#### a. GitHub (para cada membro)  

   - Nome do repositório: *checkpoint2*

#### b. Upload no Portal do Aluno/área de entrega de trabalhos.

   - Arquivo txt contendo a url do repositório com o código do projeto atualizado.

> Repositório: https://github.com/<nome_do_usuario>>/checkpoint2  
