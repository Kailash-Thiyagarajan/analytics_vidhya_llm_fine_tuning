# LLM Fine-Tuning Examples

This repository contains examples of different LLM fine-tuning techniques demonstrated during Analytics Vidhya DataHour session. The examples showcase various approaches to fine-tune large language models for specific tasks.

## Overview


The repository demonstrates three main approaches to LLM fine-tuning:

1. **Zero-Shot Prompting** ([instruction_zero_shot_prompting.ipynb](instruction_zero_shot_prompting.ipynb))
   - Using instruction-tuned models without additional training
   - Natural language task specification
   - No examples needed

2. **Few-Shot Prompting** ([few_shot_prompting.ipynb](few_shot_prompting.ipynb))
   - Learning from a few examples in the prompt
   - No model weight updates
   - Quick adaptation to new tasks

3. **Full Fine-Tuning** ([fine_tuning.ipynb](fine_tuning.ipynb))
   - Complete model weight updates
   - Includes implementations of:
     - Last layer fine-tuning
     - LoRA (Low-Rank Adaptation)
     - QLoRA (Quantized LoRA)
   - Benchmarking and comparison of different techniques

## Requirements

```python
torch
transformers
datasets
peft
tqdm
scikit-learn
pandas
matplotlib