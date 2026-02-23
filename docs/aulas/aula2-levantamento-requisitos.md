# Aula 2 — Técnicas, Ferramentas e Metodologias no Levantamento de Requisitos

**Unidade:** Levantamento de Requisitos | **Semana 1** | ⏱️ 50 minutos

---

## 🎯 O que você vai aprender hoje

Na aula anterior, você aprendeu o que são requisitos e suas classificações. Agora vamos um passo além: como **coletar** esses requisitos na prática? Quais ferramentas e metodologias os profissionais usam no dia a dia?

Ao final desta aula, você vai conseguir:

- Distinguir requisitos funcionais e não funcionais em exemplos reais
- Compreender a diferença entre metodologias **ágeis** e **tradicionais** no levantamento de requisitos
- Conhecer as principais ferramentas usadas pela indústria

---

## 🔍 Aprofundando com um exemplo real

Vamos analisar o levantamento de requisitos de um **software hipotético de e-commerce** para fixar a diferença entre os dois tipos:

### Requisitos Funcionais

**1. Definição do escopo do produto**
- Objetivo: determinar o que o software deve fazer
- Como: reuniões com os stakeholders (partes interessadas) para identificar as funcionalidades desejadas
- Exemplo: *"O sistema deve permitir que os usuários se registrem e criem contas com e-mail e senha"*

**2. Análise das necessidades do usuário**
- Objetivo: entender o que os usuários realmente precisam
- Como: entrevistas com clientes em potencial e análise de feedbacks
- Exemplo: *"O sistema deve oferecer um carrinho de compras onde os usuários podem adicionar e remover produtos antes do checkout"*

### Requisitos Não Funcionais

**3. Performance e escalabilidade**
- Objetivo: definir padrões de desempenho sob diferentes cargas de uso
- Como: discussão com a equipe de desenvolvimento sobre expectativas de tempo de resposta
- Exemplo: *"O sistema deve suportar pelo menos 10.000 usuários simultâneos sem degradação de desempenho"*

**4. Segurança e conformidade**
- Objetivo: garantir proteção dos dados e conformidade legal
- Como: consulta a especialistas em segurança
- Exemplo: *"Todos os dados de pagamento devem ser criptografados usando padrões de criptografia atuais"*

---

## ⚖️ Resumindo a diferença

| | Requisitos Funcionais | Requisitos Não Funcionais |
|---|---|---|
| **São** | Especificações do que o sistema deve fazer | Parâmetros de como o sistema deve ser |
| **Descrevem** | Funções e características que o usuário usa diretamente | Desempenho, segurança, conformidade, portabilidade, usabilidade |
| **Pergunta** | "O sistema faz isso?" | "O sistema funciona bem nisso?" |

---

## 🏗️ Metodologias: Ágil x Tradicional

A forma de levantar requisitos varia bastante dependendo da metodologia do projeto.

### 📐 Metodologia Tradicional — Modelo em Cascata

No modelo em cascata, o levantamento de requisitos é uma **fase separada e completa** antes de qualquer desenvolvimento. Funciona assim:

1. Os requisitos são levantados **primeiro**, em uma fase inicial e bem definida
2. Toda a documentação é feita de forma **detalhada** para evitar mudanças no futuro
3. Os requisitos são registrados em um documento formal chamado **SRS** (*Software Requirements Specification*)
4. Todos os stakeholders precisam **aprovar** antes de avançar para a próxima fase

**Vantagem:** documentação completa e previsibilidade  
**Desvantagem:** pouca flexibilidade para mudanças no meio do caminho

### 🔄 Metodologia Ágil

Nas metodologias ágeis (como Scrum e Kanban), os requisitos são coletados e refinados **de forma contínua**, ao longo de todo o projeto, em ciclos curtos chamados *sprints*.

- Os requisitos são escritos como **histórias de usuário** (*user stories*), no formato: *"Como [usuário], eu quero [funcionalidade] para [benefício]"*
- São priorizados em uma lista chamada **backlog** e entregues aos poucos
- Mudanças de requisitos são bem-vindas — o produto evolui com o feedback

---

## 🛠️ Ferramentas usadas na indústria

Existem ferramentas digitais que ajudam a registrar, organizar e rastrear requisitos ao longo do projeto:

**JIRA (Atlassian)**
Muito popular em equipes ágeis. Serve para rastrear o progresso, gerenciar o backlog e documentar histórias de usuário e bugs.

**Microsoft Azure DevOps**
Suite completa que integra planejamento de projetos, controle de versão e rastreamento de requisitos em um único ambiente.

> 💡 Você vai usar ferramentas como essas nas próximas unidades. Por enquanto, o importante é saber que elas existem e para que servem.

---

## ✏️ Quiz — Fixando o conteúdo

> 📋 **Registro no caderno** | ⏱️ 10 minutos

Para cada afirmação abaixo, escreva se é um **RF** (Requisito Funcional) ou **RNF** (Requisito Não Funcional) e justifique em uma frase:

**1.** "O software deve ser capaz de processar 100 transações por minuto."

**2.** "O software deve ser compatível com os principais navegadores web."

**3.** "O software deve permitir que os usuários criem uma conta e façam login."

**4.** "O software deve implementar criptografia SSL para todas as transações."

**5.** "O sistema deve permitir a edição de perfil pelo usuário."

**6.** "O sistema deve garantir a privacidade dos dados do usuário seguindo as normas de proteção de dados."

---

### ✅ Gabarito comentado

| # | Tipo | Por quê? |
|---|---|---|
| 1 | **RNF** | Processar 100 transações/min é uma medida de desempenho — um atributo do sistema, não uma funcionalidade |
| 2 | **RNF** | Compatibilidade com navegadores é um atributo de portabilidade |
| 3 | **RF** | Criar conta e fazer login é uma funcionalidade direta que o usuário executa |
| 4 | **RNF** | Criptografia SSL define *como* as transações devem ser seguras, não *o que* o sistema faz |
| 5 | **RF** | Editar perfil é uma ação que o usuário realiza no sistema |
| 6 | **RNF** | Garantir privacidade segundo a LGPD é um atributo de segurança e conformidade |

---

## 🔁 O que vimos hoje

1. Requisitos funcionais e não funcionais aparecem juntos em projetos reais — ambos são essenciais
2. A metodologia **tradicional** levanta todos os requisitos antes de começar; a **ágil** refina os requisitos ao longo do projeto
3. Ferramentas como **JIRA** e **Azure DevOps** ajudam a organizar e rastrear requisitos em equipe

---

## 📖 Para se aprofundar

- 🎥 **Attekita Dev** — "Esqueça isso e seu projeto estará condenado (Análise de Requisitos)": [youtube.com/watch?v=rVbJ7ykuLig](https://www.youtube.com/watch?v=rVbJ7ykuLig)
- 🎥 **Alura** — "Engenharia de requisitos: como levantar, documentar e validar": [cursos.alura.com.br](https://cursos.alura.com.br/course/engenharia-requisitos/task/69583)
- 📚 VAZQUEZ, C. E.; SIMÕES, G. S. *Engenharia de Requisitos: Software Orientado ao Negócio*. São Paulo: Brasport, 2016.

---

*Técnico em Desenvolvimento de Sistemas — Educação Profissional Paulista*
