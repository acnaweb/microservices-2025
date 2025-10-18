# SOA - Microservices and Web Engineering  

## Check Point 2/3º semestre/2025 - Prof. Antonio Carlos de Lima Júnior  

### Instruções Gerais

- Atividade a ser desenvolvida em grupos de até 3 pessoas.  
- A entrega deve ser realizada **apenas por um representante do grupo**.  
- Observe o enunciado abaixo e siga as instruções a partir do item 1.  

---

### Projeto  

Usar a aplicação desenvolvida no checkpoint 1.

---

### Atividades  

**1. (1 ponto)** - Criar Action de Continuous Integration com as tarefas:
- Execução de testes unitários.
- Empacotamento da aplicação Java com Maven.

Disparar esta Action a partir do evento push nas branchs:
  - develop
  - feature
  - hotfix

**2. (1 ponto)** - Criar Action de Continuous Delivery com as tarefas:
- Upload da imagem Docker no Docker Hub.

Disparar esta Action a partir do evento pull request nas branchs:
  - main

**2. (1 ponto)** - Criar Action de geração de Tag de Release:
- Gerar documentação da versão.
- Gerar Release e Tag da versão.

Disparar esta Action a partir do evento push nas branchs:
  - main
    
---

### Instruções de Entrega  

#### a. GitHub e Docker Hub  

- O repositório no GitHub e o repositório no Docker Hub devem possuir o **mesmo nome**.  

#### b. Upload no Portal do Aluno / Área de Entrega de Trabalhos  

- Enviar um arquivo `.txt` contendo as seguintes informações:  
  - URL do repositório no GitHub com o código do projeto atualizado.  
  - URL do repositório no Docker Hub com a imagem publicada.  
  - Nomes dos membros do grupo.

> Exemplo GitHub: https://github.com/<nome_do_usuario>/checkpoint1  
> Exemplo Docker Hub: https://hub.docker.com/r/<nome_do_usuario>/checkpoint1
