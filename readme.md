# Fine-Tuning DistilBERT with LoRA for Binary Classification

This project demonstrates how to fine-tune a DistilBERT model using Low-Rank Adaptation (LoRA) for binary classification tasks. The notebook Fine_tuning_an_LLM_with_LoRA.ipynb provides a step-by-step guide to setting up the environment, loading datasets, training the model, and evaluating its performance.

## DistilBERT and LoRA

DistilBERT is a smaller with 66M parameters, faster, cheaper, and lighter version of BERT. LoRA (Low-Rank Adaptation) is a technique to adapt pre-trained language models to new tasks efficiently. This project combines these two techniques to perform binary classification.

## Dataset

The dataset used in this project is the IMDB movie review dataset. It consists of 50,000 movie reviews labeled as positive or negative. The dataset is split into 25,000 reviews for training and 25,000 reviews for testing.

## Preprocessing data

The data is preprocessed by tokenizing the text and converting it into input features that can be fed into the model. The labels are also converted into numerical values for training.
