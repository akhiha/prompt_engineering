
---
title: Advanced Prompt Engineering
author: Your Name
date: 2025-07-17
---

# Welcome

*“Why did the prompt engineer break up with the language model?**  
*Because every time they wanted a simple answer, it started a new chain of thought!”*

---

## Session Roadmap (90 min)

1. Recursive prompting  
2. Program‑aided prompting (ReAct)  
3. Prompt chaining (LangChain)  
4. Embeddings 101  
5. Prompt injection & defense  
6. Hands‑on + challenges

---

## 1. Recursive Prompting

**Concept**  
Split ➜ Summarise ➜ Combine ➜ Repeat until under token budget.

**Use case:** Turn a 10‑page research article into a 50‑word abstract.

Notes: Discuss map‑reduce chain, cost control.

---

## 2. Program‑Aided Prompting

**Concept**  
Let code handle deterministic sub‑tasks; LLM focuses on reasoning.

**Use case:** Carbon‑footprint calculator inside an LLM chat.

Notes: ReAct paper (Yao et al. 2023).

---

## 3. Prompt Chaining (LangChain)

Input ➜ Translate ➜ Enrich ➜ Summarise ➜ Output.

**Example:** Multi‑step travel itinerary builder.

---

## 4. Embeddings

Vectors instead of tokens; semantic search.

**Demo:** Search 100 conference abstracts.

---

## 5. Prompt Injection

Attack ↔ Defense layers (system prompt, input filter, output filter).

**Demo:** Leak grading rubric, then patch.

---

## Wrap‑up & Next Steps

* Explore local LLMs (Ollama + Llama‑3 8B)  
* Try your own use cases  
* Share feedback!

