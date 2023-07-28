# GPT-2 Fine-Tuning with Hugging Face distilgpt2

This repository showcases the process of fine-tuning the GPT-2 language model using the [🤗 Hugging Face distilgpt2](https://huggingface.co/distilgpt2). Our primary objective is to fine-tune GPT-2 on the SQuAD (Stanford Question Answering Dataset).

## Contents

- [Introduction](#introduction)
- [Setup](#setup)
- [Results](#results)

## Introduction

Fine-tuning is a crucial technique in machine learning that involves taking a pre-trained model and further training it on a specific task or dataset to adapt it to new data or optimize it for a particular objective. Pre-trained models are usually trained on large and diverse datasets, learning general patterns and representations that can be valuable for various tasks.

## Setup

To get started, install the required libraries and dependencies by running the following command:

```bash
pip install transformers datasets huggingface_hub
```

# Results

The results of the fine-tuning process are evaluated using perplexity. The trained model can be saved and shared using Hugging Face Hub.
