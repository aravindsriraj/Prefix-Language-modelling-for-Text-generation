# Prefix Language modelling for Text generation

**Problem Statement:**
Develop a prefix language model using Hugging Face and PyTorch. You can pick any dataset for a creative text generation task and you should report the perplexity metric. Hint: A subtle data preprocessing trick is required when setting the inputs and labels for implementing prefix LM.

**Model Selected:** t5-large

**Dataset Selected:** CNN daily mail

[![WandB Link](https://img.shields.io/badge/WandB-Text%20Generation%20using%20Prefixtuning-blue?style=flat&logo=wandb)](https://wandb.ai/aravindan/Prefix%20language%20modelling/runs/cqc8xj40?workspace=user-aravindsriraj)
[![Colab Link](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1gE-Pjg7yNXVciY0HRUuV8UTCl3er0SKg?usp=sharing)

### Prefix Language Modelling:

- Generalizes ARLM by allowing the model to condition on any prefix of tokens, not just the preceding ones. This enables text generation in both forward and backward directions and filling in the blanks within a text.
- More flexible and powerful, handling various tasks with a single unified architecture (e.g., text generation, summarization, completion, image generation, captioning).

### Autoregressive Language Modelling

- A simpler and common approach where the model predicts the next word in a sequence based on the preceding words, learning the likelihood of each word given its context.
- Mainly suitable for text generation tasks, creating context in the forward direction.


