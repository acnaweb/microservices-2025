# Microservice and Web Engineering - 3SIT/2024

## Check Point 3/1º semestre - Prof. Antonio Carlos de Lima Júnior

### Instruções Gerais

- Prazo de entrega: __06/05__.
- O checkpoint deverá ser desenvolvido em até 3 pessoas.
- Cada membro deve ter o projeto em seu próprio repositório no Github até a data de entrega.

### Atividades

#### 1. (_1 ponto_) - Criar o projeto conforme instruções:

> [!IMPORTANT]
> - Usar o projeto base https://github.com/acnaweb/mvc-rh

#### 2. (_0,5 ponto_) - Adicionar 3 Spring profiles: 

> * dev - porta 8080 com conexão para BD H2
> * stg - porta 8080 com conexão para BD MySQL
> * prd - porta 8080 com conexão para BD Oracle

#### 3. (_ 0,5 ponto_) - Criar o Dockerfile para aplicação Web Java

O Dockerfile deverá conter as instruções para compilação e execução da aplicação.

#### 4. (_0,5 ponto_) -  Imagem no Docker Hub 

Upload da imagem do docker hub do respectivo membro

> - nome do repositório: fiap-checkpoint3
> - tag: lastest

#### 5. (_0,5 ponto_) - Adicionar instruções no README.md do respostório

> - Comando "docker" para executar a aplicação a partir do docker hub do __respectivo membro__ com profile "dev"
> - Comando "docker" para executar a aplicação a partir do docker hub do __respectivo membro__ com profile "stg"
> - Comando "docker" para executar a aplicação a partir do docker hub do __respectivo membro__ com profile "prd"

#### 6. (_7,5 pontos_) - Desenvolver uma view conforme as instruções:

Listagem de Funcionários por cargo (mockup)

- Definir corretamente a pasta de template para criação da view
- Definir corretamente a Controller para implementação

### Entregáveis

> A validação será realizada pela navegação do endpint da listagem criada

#### 1. Github (para cada membro)

Nome do repositorio: __fiap-checkpoint3__

#### 2. Docker hub (para cada membro)

Nome do repositorio: __fiap-checkpoint3__

#### 3. Arquivo para área de entrega de trabalhos

Arquivo txt contendo as seguintes informações no exemplo abaixo:

| Aluno(a) | Github |
| --- | --- |
| Maria | https://github.com/maria/fiap-checkpoint3 |
| João | https://github.com/joao/fiap-checkpoint3 |
| Ana | https://github.com/ana/fiap-checkpoint3 |
