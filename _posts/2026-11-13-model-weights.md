---
layout: post
title: "What Are Model Weights?"
date: 2026-11-13 17:06:00 -0330
category: LLM Basics
series: LLM Basics for Beginners
order: 6
---

*An introductory website adaptation of a topic from my LinkedIn LLM Basics learning series.*

When a neural network learns, it updates numerical values known as **weights**. These parameters influence how information flows through the model and how it makes predictions.

Imagine a simple calculation where inputs contribute differently to an output. Weights determine how strongly each input contributes. Modern language models have many layers and far more complex patterns, but the central idea remains: their learned parameters influence predictions.

During training, an optimization algorithm adjusts weights to reduce prediction error on training examples. During ordinary inference, the weights are generally kept fixed while the model generates responses.

**Key idea:** Weights store learned numerical patterns, not a searchable copy of every training sentence.

---

[Explore the complete LLM Basics series](/llm-basics/) · [LinkedIn series overview](https://www.linkedin.com/pulse/llm-basics-beginners-my-learning-series-fatema-tuj-johora-b5lhc)
