# AI Systems Evolution Notes

This repository contains my personal notes while studying the evolution of modern LLMs, retrieval systems, agent architectures, and reasoning models.

The goal is not to summarize papers section by section.

Instead, I focus on understanding:

* What problem the paper was trying to solve
* Why the idea was necessary at the time
* How the method works in practice
* What impact it had on later research and production systems

Most reviews are written from the perspective of an engineer trying to understand the intuition behind the idea rather than reproduce every equation in the paper.

---

## Review Structure

Each paper is reviewed using the following format:

### 1. Problem

What limitation or bottleneck existed before this paper?

### 2. Motivation

Why was a new approach needed?

Why were previous methods insufficient?

### 3. Method

How does the proposed idea work?

The focus is on intuition and practical understanding rather than mathematical derivations.

### 4. Key Takeaways

What is the most important thing to remember from this paper?

What impact did it have on future research, open-source models, or production systems?

---

## Reading Roadmap

### Foundation Models

#### LLaMA

Understanding the design choices that became the foundation of many modern open-source LLMs.

#### RoFormer

Understanding Rotary Position Embedding (RoPE), one of the key components adopted by LLaMA and many later models.

---

### Parameter-Efficient Fine-Tuning

#### LoRA

Understanding why full fine-tuning became impractical and how low-rank adaptation changed LLM customization.

#### QLoRA

Understanding how large models can be fine-tuned on consumer GPUs through quantization.

---

### Efficient Inference

#### FlashAttention

Understanding how attention computation became dramatically faster and more memory efficient.

#### vLLM

Understanding the serving system innovations behind modern LLM inference.

---

### Alignment

#### InstructGPT

Understanding how instruction-following models emerged beyond pure next-token prediction.

#### DPO

Understanding alignment without reinforcement learning.

#### GRPO

Understanding recent reinforcement-learning approaches used in reasoning models.

---

### Retrieval Systems

#### RAG

Understanding how external knowledge can be incorporated into LLMs.

#### GraphRAG

Understanding why graph structures can improve retrieval quality and reasoning.

---

### Agent Systems

#### ReAct

Understanding how reasoning and tool usage can be combined within a single framework.

#### MemGPT

Understanding memory management for long-running AI agents.

---

### Reasoning Models

#### DeepSeek-R1

Understanding how reinforcement learning can improve reasoning ability in modern LLMs.

---

This repository assumes familiarity with the Transformer architecture and self-attention mechanisms. Therefore, "Attention Is All You Need" is not covered directly, and later papers are reviewed from the perspective of someone already familiar with the Transformer foundation.
