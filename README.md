# Experimento - PaginationHelper

Este repositório contém a tarefa de programação utilizada em um experimento controlado cujo objetivo é avaliar o impacto do uso de Inteligência Artificial generativa na autonomia técnica em atividades de desenvolvimento Java.

---

## Contexto da Pesquisa

O experimento investiga se o uso de modelos de linguagem (LLMs) durante atividades de programação influencia:

- Autonomia técnica
- Raciocínio lógico
- Tratamento de casos de borda (edge cases)
- Organização estrutural do código
- Dependência de soluções geradas por IA

A atividade proposta consiste na implementação de uma classe genérica `PaginationHelper<T>`.

---

## Descrição da Tarefa

Os participantes devem completar os métodos da classe `PaginationHelper<T>`, responsável por fornecer informações de paginação de uma coleção.

### Requisitos

- `itemCount()` → Retorna o número total de itens da coleção.
- `pageCount()` → Retorna o número total de páginas.
- `pageItemCount(pageIndex)` → Retorna a quantidade de itens em uma página ou -1 se o índice for inválido.
- `pageIndex(itemIndex)` → Retorna o índice da página correspondente ao item ou -1 se o índice for inválido.
- Os índices são baseados em zero (zero-based).
- O parâmetro `itemsPerPage` deve ser maior ou igual a 1.

---

## Estrutura Experimental

O experimento é dividido em duas fases:

### Fase 1
Implementação da tarefa com acesso à Inteligência Artificial generativa.

### Fase 2
Implementação de tarefa semelhante sem acesso à IA.

A comparação entre as fases considera:

- Correção funcional
- Complexidade ciclomática
- Tratamento de casos de borda
- Organização do código
- Comportamento durante o uso (ou ausência) da IA

---

## Estrutura do Projeto

```text
src/
├─ main/java/
│  └─ br/pucminas/experimento/service/PaginationHelper.java
└─ test/java/
   └─ br/pucminas/experimento/service/PaginationHelperTest.java
```
---

## Tecnologias Utilizadas

- Java 17
- Maven
- JUnit 5

---

Este repositório faz parte de um estudo acadêmico na área de Engenharia de Software e Inteligência Artificial aplicada à educação e prática de programação.
