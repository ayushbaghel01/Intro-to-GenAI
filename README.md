# Intro-to-GenAI
The project mainly focused on three parts i.e. Engineering a translational transformer, Question and Answer Retrieval Task and a Generative model for image genration of MNIST dataset of digits.

## Translational Transformer
We implemented a Translational Transformer model, a specialized variant of the Transformer architecture designed for `sequence-to-sequence` tasks. It's particularly effective in tasks like machine translation and text summarization due to its utilization of self-attention mechanisms.

## Question Answer Retrieval with DistilBERT
Utilizing the `distilbert-base-cased-distilled-squad` model, we developed a system for question answering tasks. This model, pre-trained on the `SQuAD dataset`, allows for efficient extraction of relevant answers from text given a specific question.

## Generative Adversarial Network (GAN) for MNIST Digit Generation
We trained a `Generative Adversarial Network (GAN)` to generate realistic hand-written digit images resembling those from the MNIST dataset. By simultaneously training a generator and a discriminator network, the GAN learns to generate `high-quality digit images` from random noise input.

These components showcase the versatility of deep learning techniques across diverse domains, from natural language processing to computer vision. Each component contributes to advancing the capabilities of artificial intelligence in solving complex real-world problems.

## Requirements
- Python 3.x
- PyTorch
- Hugging Face Transformers
- TensorFlow (for GAN)
- NumPy
- Matplotlib

## Usage
1. Ensure that you have the necessary resources (pre-trained models, datasets) downloaded or available.
2. Make sure to install the dependencies given in requirements.
