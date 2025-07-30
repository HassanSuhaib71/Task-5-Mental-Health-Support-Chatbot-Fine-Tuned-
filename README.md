# Mental Health Chatbot using Empathetic Dialogues

This notebook demonstrates how to build a simple mental health chatbot using a pre-trained language model fine-tuned on the Empathetic Dialogues dataset.

## Dataset

The dataset used in this notebook is the [Empathetic Dialogues dataset](https://www.kaggle.com/datasets/atharvjairath/empathetic-dialogues-facebook-ai) from Facebook AI. It consists of conversations grounded in emotional situations.

## Model

We use the `distilgpt2` model from the Hugging Face Transformers library as the base model and fine-tune it on the Empathetic Dialogues dataset.

## Dependencies

The following libraries are required:

- `opendatasets`
- `pandas`
- `transformers`
- `datasets`
- `evaluate`
- `accelerate`

These can be installed using pip:
