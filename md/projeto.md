# 📊 Relatório do Projeto Jira: Estruturação e Aprendizados (Portfólio)

Este documento detalha o funcionamento, a organização e tudo o que foi praticado e aprendido durante a criação deste projeto fictício no Jira Software, estruturado especificamente para compor meu portfólio profissional.

---

## 🛠️ O Que Foi Feito no Projeto?

Com base nas etapas reais de desenvolvimento de software, montei um projeto completo para um **Sistema de Agendamento e Gestão de Serviços**. A organização foi baseada em três pilares visuais extraídos do ambiente do Jira:

### 1. Divisão por Épicos e Rastreabilidade
O escopo macro do sistema foi quebrado em **5 grandes Épicos**, permitindo rastrear o andamento de cada módulo:
* **Gestão de Usuários (`KJ-1`):** Módulo de segurança, englobando Cadastro, Login e Recuperação de Senha.
* **Agendamento de Serviços (`KJ-2`):** Regras de negócio para criar, reagendar ou cancelar horários.
* **Orçamentos (`KJ-3`):** Fluxo comercial de solicitação e aprovação de ordens de serviço.
* **Acompanhamento de Serviços (`KJ-4`):** Transparência para o cliente saber o status do seu veículo/serviço.
* **Notificações (`KJ-5`):** Alertas automatizados de confirmação e atualizações de status.

### 2. Quadro Kanban com Raias de Prioridade (Swimlanes)
O fluxo de trabalho foi dividido nas colunas padrão de mercado: `Backlog` ➔ `Selected for Development` ➔ `In Progress` ➔ `Done`. Porém, para simular um time real de alta performance, utilizei **duas raias verticais (Swimlanes)**:
* **Raia `Expedite` (Urgente):** Criada exclusivamente para itens de altíssima prioridade, como testes críticos bloqueantes (`KJ-25`) ou Bugs graves em produção (ex: `KJ-22` - Histórico não exibe serviços concluídos). Esses itens furam a fila tradicional para correção imediata.
* **Raia `Everything Else` (Fluxo Normal):** Onde correm as histórias de usuário planejadas no dia a dia do projeto (como o desenvolvimento das telas de Login e Cadastro).

### 3. Engenharia de Requisitos (Escrita de User Stories)
Cada tarefa do usuário final foi escrita seguindo rigorosamente os padrões de metodologias ágeis. Um exemplo prático foi o ticket de **Cadastro (`KJ-6`)**, estruturado sob a ótica do cliente:
* **Como** cliente
* **Desejo** criar um cadastro
* **Para** acessar os serviços do site

---

## 🧠 O Que Eu Aprendi Com Este Projeto?

* **Mentalidade Ágil na Prática:** Aprendi a pegar uma ideia abstrata de software e quebrá-la de forma lógica em Épicos, Tarefas e Bugs, entendendo o ciclo de vida completo de uma entrega de valor.
* **Gerenciamento de Prioridades e SLA:** A configuração da raia *Expedite* me trouxe a visão de como um Product Owner ou Scrum Master gerencia crises (Bugs) sem paralisar completamente o time de desenvolvimento.
* **Comunicação Clara com o Time:** Escrever histórias usando a estrutura *Como/Desejo/Para* me ensinou a documentar requisitos focando no benefício real do usuário, facilitando o trabalho de desenvolvedores e testadores (QA).
* **Domínio do Jira Software:** Aprendi a operar a principal ferramenta de gestão de projetos de tecnologia do mercado mundial, configurando status, fluxos e mapeando pendências de forma profissional.