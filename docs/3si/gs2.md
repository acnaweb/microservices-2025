
# **Global Solution — Avaliação Oficial**

### **Microservices and Web Engineering — 3SIR (Sistemas de Informação)**  
**Prof. Antonio Carlos de Lima Júnior**

---

### Novas carreiras. Novas tecnologias. Infinitas possibilidades.
#### O trabalho está mudando — e você pode ajudar a construir o que vem pela frente.

Sua consultoria foi contratada para desenvolver uma **API de integração** alinhada ao tema da Global Solution. O objetivo é projetar uma API **moderna, escalável e preparada para implantação em nuvem**, utilizando **dockerização**, acompanhada de documentação completa e de um pipeline funcional de **CI/CD**.

## 📌 1. Definição do Tema

O tema do grupo deve ser determinado da seguinte forma:

- **Último dígito do RM**, ou  
- **Último dígito da soma dos RMs**, quando for trabalho em dupla.

### ➕ Exemplo
RM1: `552353`  
RM2: `92957`  
Soma: `552353 + 92957 = 645310`  
Último dígito: `0`

**Tema escolhido:**  
`0. Plataformas que conectam talentos a projetos com propósito`

---

## 🎯 2. Temas Disponíveis + Nome obrigatório do repositório

Cada tema possui um nome padronizado **OBRIGATÓRIO** para GitHub e Docker Hub:

| Nº | Tema | Repositório Oficial |
|----|-------|----------------------|
| **0** | Plataformas que conectam talentos a projetos com propósito | `gs-0-talent-platform` |
| **1** | Plataformas de upskilling e reskilling baseadas em IA | `gs-1-ai-upskilling` |
| **2** | Ambientes de trabalho com Realidade Virtual ou Aumentada | `gs-2-vr-ar-workspaces` |
| **3** | Ferramentas de monitoramento de bem-estar e saúde mental | `gs-3-wellbeing-monitor` |
| **4** | Aplicativos para conciliar vida pessoal e profissional | `gs-4-worklife-balance` |
| **5** | Sistemas de recrutamento ético e inclusivo com base em dados | `gs-5-ethical-recruiting` |
| **6** | Soluções gamificadas para motivação em equipes híbridas | `gs-6-gamified-teams` |
| **7** | Bots e agentes de IA como parceiros no dia a dia de trabalho | `gs-7-ai-work-bots` |
| **8** | Modelos de trabalho baseados em impacto social e sustentabilidade | `gs-8-social-impact-work` |
| **9** | Comunidades de aprendizagem colaborativa e global | `gs-9-collab-learning` |

---

## 🛠️ 3. Requisitos Técnicos da API

### ✔️ Tecnologia
- Java + Spring Boot  
- Sem banco de dados  
- Porta padrão: **8081**

### ✔️ Estrutura obrigatória
Criar **apenas uma controller**:

```
TemaController
```

Com **um único endpoint**:

### **GET `/info`**

Retornando o JSON:

```json
{
  "tema": "O nome do tema",
  "membro1": "Nome do Membro 1",
  "membro2": "Nome do Membro 2",
  "descricao": "Uma explicação textual sobre o tema"
}
```

---

## 📄 4. Documentação

A API deve conter **Swagger (OpenAPI)** acessível pela interface padrão:

Exemplos:
- `/swagger-ui.html`
- `/swagger-ui/index.html`

---

## 📦 5. Repositórios

### 🐳 Docker Hub
- Publicar a imagem Docker da aplicação.
- Enviar a **URL do repositório da imagem**.

### 🐙 GitHub
- Repositório com **todo o código-fonte + workflows + Dockerfile**.
- Utilizar **obrigatoriamente** o nome oficial do tema.
- Enviar a **URL do repositório GitHub**.

---

## ⚙️ 6. GitHub Actions — CI/CD (10 pontos)

## **6.1 Automação de Versão (Versioning) — 4 pontos**

Workflow deve:

- Gerar **tags automáticas** no GitHub  
- Ser disparado por **push na branch `main`**  
- Estar presente no repositório (arquivo YAML)

### ✔ Evidência obrigatória
- Execução registrada em *Actions*  
- **Tag criada automaticamente** no repositório

---

## **6.2 Continuous Integration (CI) — 3 pontos**

Workflow deve executar:

- Build da aplicação  
- Testes unitários  
- Build da imagem Docker (verificação)  
- Ser disparado por **push** nas branches:
  - `feature/**`
  - `release`
  - `hotfix`

### ✔ Evidência
Execução registrada em *Actions*.

---

## **6.3 Continuous Delivery (CD) — 3 pontos**

Workflow deve:

- Enviar imagem automaticamente ao **Docker Hub**  
- Ser disparado por **pull request** na branch `develop`

### ✔ Evidência
- Execução registrada em *Actions*  
- Imagem atualizada no Docker Hub
---

### ⚠️ ATENÇÃO — NOMES DOS REPOSITÓRIOS (OBRIGATÓRIO)

Os nomes dos repositórios **DEVEM ser exatamente os mesmos** definidos na tabela *Repositório Oficial*.  
Essa regra é **obrigatória** e faz parte da nota final.

❗ Se o nome for diferente, o grupo **perderá pontos** e poderá ter falhas nos workflows de CI/CD.

✔ Exemplos válidos:  
- `gs-0-talent-platform`  
- `gs-7-ai-work-bots`

✘ Exemplos inválidos:  
- `trabalho-gs`  
- `tema7-api`  
- `gs7aiworkbots`  
- `gs-07-ai-work-bots` *(não alterar estrutura)*

---

### 📘 README Obrigatório no Repositório

O repositório GitHub deverá conter um arquivo **`README.md` obrigatório**, incluindo:

- **Nome completo de todos os membros do grupo**
- **RM de cada membro**
- **Descrição do tema escolhido**
- **Resumo da finalidade da API**
- **Instruções de execução local (como rodar o projeto)**
- **URL da imagem no Docker Hub**
- **Descrição dos workflows CI/CD implementados**

A ausência dessas informações implicará em **perda de pontos**.

---

## 📘 7. Resumo dos Entregáveis

| Item | Entrega |
|------|---------|
| API Java Spring Boot | ✔ |
| Controller TemaController | ✔ |
| GET /info | ✔ |
| JSON com descrição | ✔ |
| Documentação Swagger | ✔ |
| Repositório GitHub (padrão obrigatório) | ✔ |
| README com nomes dos membros | ✔ |
| Imagem no Docker Hub | ✔ |
| Workflow Versioning | ✔ |
| Workflow CI | ✔ |
| Workflow CD | ✔ |


