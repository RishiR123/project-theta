# 🧬 Deep AI & Foundations

Go beyond the surface level. This section covers the "why" and "how" of AI—the math, the architecture, and the research that makes it all possible.

---

## 🏗️ Core Architecture: The Transformer
Modern AI (LLMs like ChatGPT, Claude, etc.) is built on the **Transformer** architecture.

> [!IMPORTANT]
> **Key Paper:** [*"Attention is All You Need"* (2017)](https://arxiv.org/abs/1706.03762)
> This paper introduced the concept of "Self-Attention," allowing models to understand the relationship between words in a sentence regardless of their distance.

### The Self-Attention Mechanism
Imagine a sentence: *"The dog didn't cross the street because **it** was too tired."*
How does the AI know if "**it**" refers to the dog or the street?
- **Self-Attention** gives weights to every word.
- In this case, "it" gets a high weight connection to "dog".

---

## 🧮 Mathematical Foundations
You don't need a PhD, but if you want to understand "Deep AI," these are the pillars:

1. **Linear Algebra**: Scalars, Vectors, Matrices, and Tensors. Think of a Tensor as a multi-dimensional array of numbers that representative features of data.
2. **Calculus (Backpropagation)**: How the model learns from its mistakes. It uses gradients (derivatives) to adjust its internal "weights" to reduce error.
3. **Probability & Statistics**: AI models don't "know" facts; they predict the most probable next token based on their training data.

---

## 📜 High-Impact Research Papers
| Topic | Title | Link |
|-------|-------|------|
| **The Foundation** | Attention Is All You Need | [arXiv](https://arxiv.org/abs/1706.03762) |
| **Generative Modeling** | Generative Adversarial Nets (GANs) | [Arxiv](https://arxiv.org/abs/1406.2661) |
| **Diffusion (Images)** | Denoising Diffusion Probabilistic Models | [arXiv](https://arxiv.org/abs/2006.11239) |
| **RLHF** | Training language models to follow instructions | [OpenAI](https://openai.com/research/instruction-following) |

---

## 🧪 Open Source Models (The Weights)
Want to run "Deep AI" locally? Check out these base models:
- **Llama 3 (Meta)**: The gold standard for open-weights LLMs.
- **Mistral / Mixtral**: High-efficiency MoE (Mixture of Experts) models.
- **OpenCLIP**: The backbone of many image-understanding systems.

---

*Project Theta — It's Just AI.*
