## Project Overview
This mini-project was undertaken to bridge the gap between theoretical understanding of Large Language Models (LLMs) and practical, hands-on implementation. The primary objective was to experiment with fine-tuning an open-source LLM, evaluate its behavior against a base model, and gain deeper intuition about how model adaptation works in practice.
Rather than optimizing for state-of-the-art performance, the focus of this project was learning-oriented: understanding the fine-tuning pipeline, experimentation workflow, and the practical realities of working with open-source LLMs using PyTorch and Hugging Face.

## Learning Objectives
The project aimed to:
- Apply theoretical concepts from NLP and Generative AI in a practical setting
- Gain hands-on experience with LLM fine-tuning workflows
- Understand how fine-tuning impacts model behavior for task-specific use cases
- Explore evaluation strategies such as A/B testing for comparing model outputs
- Build familiarity with PyTorch and Hugging Face tooling for LLM experimentation

## Key Outcomes and Observations

The performance difference between the base model and the fine-tuned model was relatively modest. However, this outcome itself was an important learning signal, highlighting that:
- Many modern base models are already well-aligned for general tasks

- Fine-tuning often results in incremental but meaningful behavioral improvements, rather than dramatic changes

- The value of fine-tuning lies in task alignment and consistency, not just raw output quality

Despite the subtle quantitative gains, the project provided clear qualitative insights into how fine-tuning helps evolve a general-purpose LLM to better suit a specific objective.

## Technical Skills and Concepts Explored

Through this project, the following technical areas were explored and implemented:

### LLM Fine-Tuning & Evaluation

- Supervised fine-tuning fundamentals

- Designing and conducting A/B tests to compare base and fine-tuned model behavior

- Understanding overfitting risks and model generalization

- Behavioral evaluation beyond loss metrics

### Frameworks & Tooling

- PyTorch for training, experimentation, and debugging LLMs

- Hugging Face Transformers for:

  - Tokenization

  - Loading pretrained models

  - Managing fine-tuning workflows

- Practical exposure to the strengths and limitations of free, open-source LLMs

### Core Theoretical Foundations

- Fundamentals of transformer architectures

- Attention mechanisms:

  - Self-attention

  - Causal attention

  - Multi-head attention

- Overview of RLHF concepts and different fine-tuning strategies based on task requirements

##  Reflection and Learnings
This project was highly rewarding from a learning perspective. Implementing fine-tuning end-to-end helped solidify concepts that are easy to overlook when studying LLMs purely from a theoretical standpoint. It also provided a new perspective on how LLM behavior is shaped not only by model architecture, but by data quality, evaluation strategy, and iteration.

The experience has significantly strengthened my foundational understanding of LLMs and has prepared me for more advanced projects in Natural Language Processing and Generative AI, including future work involving custom SLM/LLM experimentation.

A major source of insight throughout this project was the book _“Build a Large Language Model from Scratch” by Sebastian Raschka, which helped clarify many fundamental concepts—particularly around transformers and attention mechanisms—that are often abstracted away when using high-level frameworks.

 ## Conclusion

The goal of this project was to build strong fundamentals, practical intuition, and confidence in working with LLMs. While the empirical results were intentionally modest, the learning outcomes were substantial. The project successfully achieved its objective of deepening both theoretical understanding and hands-on capability in fine-tuning and evaluating large language models.
