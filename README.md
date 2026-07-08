# Medical Chatbot using Parameter-Efficient Fine-Tuning (LoRA)

## Overview

This project develops a medical chatbot by fine-tuning a pre-trained Large Language Model (LLM) on medical question-answering data using Low-Rank Adaptation (LoRA). The objective is to build a lightweight domain-specific assistant capable of generating medically relevant responses while reducing computational and memory requirements compared to full model fine-tuning.

This project was completed as part of the ZAKA Machine Learning Diploma.

---

## Objectives

- Fine-tune a pre-trained LLM for medical question answering
- Apply Parameter-Efficient Fine-Tuning (LoRA)
- Generate responses to unseen medical questions
- Evaluate model performance using language-model metrics
- Analyze strengths, limitations, and possible improvements

---

## Dataset

**Dataset:** Medical Meadow – WikiDoc Patient Information

The dataset contains medical questions and corresponding answers covering a wide range of health topics.

---

## Model

- Base Model: Falcon-RW-1B
- Fine-tuning: LoRA (PEFT)
- Task: Causal Language Modeling

---

## Technologies

- Python
- PyTorch
- Hugging Face Transformers
- PEFT (LoRA)
- Datasets
- Google Colab

---

## Workflow

1. Load and preprocess the dataset
2. Tokenize medical question-answer pairs
3. Load the pre-trained language model
4. Configure LoRA adapters
5. Fine-tune the model
6. Generate responses to medical questions
7. Evaluate model performance
8. Analyze limitations and future improvements

---

## Sample Results

The fine-tuned chatbot was tested on both dataset examples and unseen medical questions to evaluate its ability to generate coherent and medically relevant responses.

Example:

**Question**

> What are the symptoms of diabetes?

**Generated Response**

> *(Insert one of your model's outputs here.)*

---

## Evaluation

The project evaluates the model using:

- Training Loss
- Training Perplexity

The generated responses were also assessed qualitatively for:

- Medical relevance
- Fluency
- Hallucinations
- Response completeness

---

## Future Improvements

- Evaluate using additional benchmarks (BLEU, ROUGE, BERTScore)
- Experiment with larger instruction-tuned models
- Apply Retrieval-Augmented Generation (RAG)
- Improve factual consistency and reduce hallucinations
- Explore Agentic AI workflows for medical assistance

---

## Repository Structure

```
Medical_Chatbot.ipynb
README.md
requirements.txt
images/
```

---

## Author

**Eman Abuhamra**
