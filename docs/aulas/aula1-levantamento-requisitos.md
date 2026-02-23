# Aula 1 — O que são Requisitos de Software?

**Unidade:** Levantamento de Requisitos | **Semana 1** | ⏱️ 50 minutos

---

## 🎯 O que você vai aprender hoje

Antes de escrever uma linha de código, qualquer sistema precisa ser planejado. Esse planejamento começa com uma pergunta simples: **o que esse sistema precisa fazer?** A resposta para essa pergunta está nos **requisitos de software**.

Ao final desta aula, você vai conseguir:

- Explicar o que são requisitos de software e por que eles existem
- Reconhecer a diferença entre requisitos **funcionais** e **não funcionais**
- Identificar exemplos reais de cada tipo

---

## 💡 Vamos começar com um exemplo real

Imagine que você foi contratado para ajudar a criar um aplicativo de banco digital — parecido com o Nubank. Esse app deve permitir que os usuários façam transações, vejam saldo e recebam notificações.

Antes de qualquer desenvolvimento, a equipe precisa definir duas coisas:

- **O que o aplicativo deve fazer** → requisitos funcionais
- **Como ele deve se comportar** → requisitos não funcionais

Simples assim. Mas muito importante.

---

## 📚 O que são Requisitos?

**Requisitos** são descrições detalhadas do comportamento esperado de um sistema — as condições que ele precisa satisfazer para ser considerado "pronto" e útil pelos seus usuários.

Pense nos requisitos como a **planta de uma construção**: antes de levantar paredes, o engenheiro precisa saber onde vai cada cômodo, quantas tomadas haverá, se vai ter elevador. No desenvolvimento de software, os requisitos cumprem esse mesmo papel.

> 📝 **Tome nota**
> A prática de definir requisitos faz parte de uma disciplina chamada **Engenharia de Requisitos**: o processo de coletar, analisar, documentar e manter as necessidades de um sistema ao longo de todo o projeto.

---

## 🛠️ Para que servem os requisitos?

A função principal do levantamento de requisitos é **garantir que o produto final atenda às necessidades do usuário** — evitando retrabalho, mal-entendidos e custos extras por mudanças tardias.

Um erro muito comum em projetos de software é começar a programar sem entender direito o problema. O resultado? Um sistema que "funciona", mas não resolve o que o cliente precisava.

> ⚠️ **Importante**
> Para um bom levantamento de requisitos, são essenciais: **comunicação clara** com o cliente, **compreensão profunda** do negócio e **atenção aos desafios técnicos** do projeto.

---

## 📋 Tipos de Requisitos

### ✅ Requisitos Funcionais

São as **ações** que o sistema deve ser capaz de realizar. Eles respondem à pergunta: **"O que o sistema faz?"**

Exemplos:
- O sistema deve permitir que o usuário faça login com e-mail e senha
- O sistema deve enviar um e-mail de confirmação após o cadastro
- O sistema deve exibir o extrato das últimas 30 transações

### ⚙️ Requisitos Não Funcionais

Descrevem as **qualidades e atributos** do sistema. Respondem à pergunta: **"Como o sistema deve ser?"**

Exemplos:
- O sistema deve suportar ao menos 10.000 usuários simultâneos
- O tempo de resposta de qualquer página deve ser inferior a 2 segundos
- Todos os dados devem ser criptografados durante a transmissão

| | Requisitos Funcionais | Requisitos Não Funcionais |
|---|---|---|
| **Pergunta** | O que o sistema faz? | Como o sistema deve ser? |
| **Foco** | Funcionalidades e comportamentos | Desempenho, segurança, usabilidade |
| **Exemplo** | Permitir login com e-mail e senha | Responder em menos de 2 segundos |

---

## ✏️ Atividade — Análise de Situação-Problema

> 📋 **Registro no caderno** | 👥 Individual ou em grupos de até 4 pessoas | ⏱️ 20 minutos

### Contexto

Seu *squad* foi contratado pela **Clínica Saúde & Vida**, que deseja melhorar a experiência dos pacientes com um novo **aplicativo de agendamento de consultas**.

O app deve permitir:
- Marcar, reagendar ou cancelar consultas
- Receber lembretes automáticos de check-ups futuros
- Ver instruções de preparação para exames e procedimentos

Sua equipe foi encarregada de iniciar o **levantamento de requisitos iniciais**, garantindo que o app seja funcional, fácil de usar e que melhore a gestão do tempo dos médicos.

---

### Questões para responder no caderno

**1.** Quais são as principais funcionalidades que o aplicativo deve oferecer para simplificar o processo de agendamento de consultas para os pacientes?

**2.** Como o aplicativo pode ajudar na gestão do tempo dos médicos e reduzir o número de consultas não comparecidas ou canceladas de última hora?

**3.** Que medidas de segurança devem ser implementadas para proteger as informações sensíveis dos pacientes?

---

### 💡 Gabarito sugerido (leia só depois de tentar!)

**Funcionalidades principais (RF):**
- **Agendamento online:** paciente escolhe horário e médico disponíveis
- **Gerenciamento de consultas:** reagendamento e cancelamento com facilidade
- **Lembretes e notificações:** envio automático por e-mail ou SMS antes da consulta

**Gestão do tempo dos médicos (RF + RNF):**
- **Calendário para médicos:** visão clara da agenda diária
- **Lista de espera:** preencher horários vagos automaticamente
- **Confirmação 24h antes + check-in online:** reduz faltas de última hora

**Segurança (RNF):**
- **Autenticação em dois fatores** para acessar dados pessoais
- **Criptografia de dados** durante transmissão e em repouso
- **Conformidade com a LGPD** — legislação brasileira de proteção de dados

---

## 🔁 O que vimos hoje

1. Requisitos são a base de qualquer projeto de software — como uma planta para a construção
2. **Requisitos funcionais** descrevem o que o sistema faz; **não funcionais** descrevem como ele deve ser
3. Levantar bem os requisitos evita retrabalho e garante que o sistema entregue valor real ao usuário

---

## 📖 Para se aprofundar

- 🎥 **Bóson Treinamentos** — "O que é levantamento de requisitos": [youtube.com/watch?v=VcOeM2AD8Yk](https://www.youtube.com/watch?v=VcOeM2AD8Yk)
- 📚 VAZQUEZ, C. E.; SIMÕES, G. S. *Engenharia de Requisitos: Software Orientado ao Negócio*. São Paulo: Brasport, 2016.

---

*Técnico em Desenvolvimento de Sistemas — Educação Profissional Paulista*
