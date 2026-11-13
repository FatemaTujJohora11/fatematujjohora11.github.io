---
layout: post
title: "What Are Embeddings?"
date: 2026-11-13 17:03:00 -0330
category: LLM Basics
series: LLM Basics for Beginners
order: 3
---

*An introductory website adaptation of a topic from my LinkedIn LLM Basics learning series.*

A language model cannot directly perform mathematical operations on written words. After tokenization, the model looks up a learned **embedding** for each token.

An embedding is a list of numbers, also called a **vector**. Training adjusts these values so the model can use them to represent useful patterns and relationships.

Think of an embedding as a numerical starting representation. Inside the model, later layers combine that information with surrounding context.

**Why does this matter?** Embeddings help transform discrete token IDs into representations that neural networks can process.

**Key idea:** An embedding is not a dictionary definition; it is a learned numerical representation.

---

[Explore the complete LLM Basics series](/llm-basics/) · [LinkedIn series overview](https://www.linkedin.com/pulse/llm-basics-beginners-my-learning-series-fatema-tuj-johora-b5lhc)
