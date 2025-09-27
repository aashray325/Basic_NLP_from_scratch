# Basic NLP from Scratch

This repository contains a basic **Natural Language Processing (NLP)** model that I implemented from scratch to deepen my understanding of fundamental NLP concepts, such as **word embeddings**, **RNNs**, and the underlying mathematics. The primary goal of this project was to learn the concepts and build the model manually without relying on high-level libraries.

**Key Features:**
- Basic implementation of a Recurrent Neural Network (RNN) for sequence prediction.
- Focus on educational purposes to understand the inner workings of NLP.

## Project Overview

This project uses a very basic RNN architecture with custom word embeddings for sequence-to-sequence learning. It is designed to process text data in a very minimalistic way, only handling single-word input and output. The model is built from the ground up to demonstrate the essential concepts in NLP.

While this model is simple and does not scale well for complex applications, it serves as a foundational starting point for understanding more advanced techniques used in NLP.

## Limitations

- **Single-word Input/Output:** Currently, the model works with one input word and one output word. There are no mechanisms for handling multi-word inputs or generating multi-word outputs.
- **Basic Architecture:** The neural network used is quite simple and lacks the complexity of modern NLP models.
- **Training Data:** The model is trained on a very small dataset for demonstration purposes. It would require a much larger and more diverse dataset for practical use.

## Future Work

Future work includes, but is not limited to:
1. **Improving the model architecture** by increasing the number of neurons and adding more layers, hyperparameter training, learning rates etc.
2. **Switching from bi-grams to n-grams** to capture more contextual information in the input.
3. **Expanding the input dataset** to improve the model's generalization capabilities.
4. **Fine-tuning pre-trained word embeddings** (such as Word2Vec, GloVe) using domain-specific data to better handle real-world text.
5. **Developing a fine-tuned chatbot** that can engage in more sophisticated conversations which can generate entire texts and sentences and also can take in multi word inputs






