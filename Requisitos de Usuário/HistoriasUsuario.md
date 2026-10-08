# Histórias de Usuário

## US01 — Autenticação

**História de usuário:**  
Como usuário, quero me autenticar no sistema, para acessar meus registros de exercícios.

**Critérios de aceitação:**
- O sistema deve permitir a autenticação do usuário.
- Usuários autenticados devem acessar as funcionalidades restritas à sua conta.
- Usuários não autenticados não devem acessar o registro nem o histórico de exercícios.

**Prioridade:** Alta

**Requisitos relacionados:**  
RF01, RF07, RF08, RNF04

**Estimativa:**

---

## US02 — Seleção da região muscular

**História de usuário:**  
Como usuário, eu quero selecionar a região muscular que desejo exercitar, para receber exercícios direcionados à região escolhida.

**Critérios de aceitação:**

- O usuário deve conseguir visualizar as regiões musculares disponíveis.
- O usuário deve conseguir selecionar uma região muscular.
- O sistema deve registrar a região muscular selecionada.
- O usuário deve conseguir alterar a região muscular selecionada antes de prosseguir.
- A região muscular selecionada deve ser utilizada nas recomendações de exercícios.

**Prioridade:** Alta

**Requisitos relacionados:**  
RF02

---

## US03 — Recomendação de exercícios

**História de usuário:**  
Como usuário, quero visualizar exercícios compatíveis com os critérios informados, para escolher um exercício adequado.

**Critérios de aceitação:**
- O sistema deve apresentar exercícios compatíveis com os critérios informados.
- O usuário deve conseguir selecionar um exercício da lista.
- O sistema deve informar quando não houver exercícios compatíveis.

**Prioridade:** Alta

**Requisitos relacionados:**  
RF04, RF05, RF06, RNF05

**Estimativa:** 

---

## US04 — Detalhes do exercício

**História de usuário:**  
Como usuário, quero visualizar os detalhes de um exercício, para obter informações antes de realizá-lo.

**Critérios de aceitação:**
- O usuário deve conseguir acessar os detalhes de um exercício selecionado.
- As informações apresentadas devem corresponder ao exercício selecionado.

**Prioridade:** Média

**Requisitos relacionados:**  
RF05, RF06

---

## US05 — Registro de exercício realizado

**História de usuário:**  
Como usuário, eu quero registrar um exercício como realizado para acompanhar minhas atividades físicas.

**Critérios de aceitação:**

- O usuário deve conseguir registrar um exercício como realizado.
- O usuário deve conseguir confirmar o registro do exercício.
- Após a confirmação, o exercício deve constar no histórico do usuário que realizou o registro.
- Usuários não autenticados não devem conseguir registrar exercícios.

**Prioridade:** Alta

**Requisitos relacionados:**  
RF01, RF07, RF08, RNF04

**Estimativa:**

---

## US06 — Consulta ao histórico

**História de usuário:**  
Como usuário, eu quero consultar meu histórico de exercícios para acompanhar as atividades que registrei como realizadas.

**Critérios de aceitação:**

- O usuário deve conseguir acessar seu histórico.
- O histórico deve apresentar os exercícios registrados como realizados pelo usuário.
- O usuário deve visualizar somente seus próprios registros.
- Usuários não autenticados não devem conseguir consultar o histórico.

**Prioridade:** Média

**Requisitos relacionados:**  
RF01, RF07, RF08, RNF04, RNF05

**Estimativa:**

---

## US07 — Informar restrições físicas

**História de usuário:**  
Como usuário, eu quero informar minhas restrições físicas, para receber exercícios compatíveis com minhas limitações.

**Critérios de aceitação:**

- O usuário deve conseguir informar suas restrições físicas.
- O usuário deve conseguir informar mais de uma restrição, quando necessário.
- O usuário deve conseguir alterar ou remover uma restrição informada.
- As restrições informadas devem ser consideradas nas recomendações de exercícios.

**Prioridade:** Alta

**Requisitos relacionados:**  
RF03
