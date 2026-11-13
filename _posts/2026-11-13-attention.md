---
layout: post
title: "What Is Attention in an LLM?"
date: 2026-11-13 17:04:00 -0330
category: LLM Basics
series: LLM Basics for Beginners
order: 4
---

*An introductory website adaptation of a topic from my LinkedIn LLM Basics learning series.*

Words in a sentence do not carry meaning in isolation. Their relationships with nearby and distant words often matter.

**Attention** is a mechanism that lets a transformer combine information from different token positions when building contextual representations.

Consider: **"The student opened the book because she needed to study."** Understanding a word such as *she* can depend on other words in the sentence. Attention helps the model use relevant context.

In a transformer, multiple attention heads can learn different patterns. In autoregressive text generation, causal attention prevents a position from looking ahead at future tokens.

**Key idea:** Attention helps tokens use context; it is not proof that a model reasons like a person.

---

[Explore the complete LLM Basics series](/llm-basics/) · [LinkedIn series overview](https://www.linkedin.com/pulse/llm-basics-beginners-my-learning-series-fatema-tuj-johora-b5lhc)
