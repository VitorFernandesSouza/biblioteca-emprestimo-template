# PaginationHelper Experiment

This repository contains the programming task used in a controlled experiment designed to evaluate the impact of generative AI assistance on technical autonomy in Java development.

## Research Context

The experiment investigates whether the use of large language models (LLMs) during programming activities influences:

- Technical autonomy
- Logical reasoning
- Handling of edge cases
- Code structure quality
- Dependence on AI-generated solutions

The task involves implementing a generic `PaginationHelper<T>` class in Java.

## Task Description

Participants must complete the methods of the `PaginationHelper<T>` class, which provides paging information for a collection.

### Requirements

- `itemCount()` → returns total number of items.
- `pageCount()` → returns total number of pages.
- `pageItemCount(pageIndex)` → returns number of items on a page or -1 if invalid.
- `pageIndex(itemIndex)` → returns page index for an item or -1 if invalid.
- Indices are zero-based.
- `itemsPerPage` must be ≥ 1.

## Experimental Design

The experiment is structured in two phases:

- Phase 1: Task completed with access to generative AI.
- Phase 2: Similar task completed without AI assistance.

Comparative analysis includes:

- Functional correctness
- Cyclomatic complexity
- Edge case handling
- Code organization
- Behavioral interaction with AI

## Project Structure
src/
├─ main/java/
│ └─ br/pucminas/experimento/service/PaginationHelper.java
└─ test/java/
└─ br/pucminas/experimento/service/PaginationHelperTest.java

## Technical Stack

- Java 17
- Maven
- JUnit 5

---

This repository is part of an academic study on generative AI and software engineering education.
