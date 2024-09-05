# NLP Tutorials: HuggingFace and PyTorch

This repository contains two tutorials introducing the HuggingFace and PyTorch ecosystems for Natural Language Processing (NLP) tasks. These tutorials are designed for students and researchers looking to get started with state-of-the-art NLP frameworks and tools, and they provide practical, hands-on examples that focus on building and training NLP models.

It is used as a tutorial on Practical Implementations for NLP class of Georgia Tech.

## Table of Contents

- [Introduction to HuggingFace 🤗](#introduction-to-huggingface-)
  - [Summary](#summary)
  - [Key Learnings](#key-learnings)
- [Introduction to PyTorch with NLP](#introduction-to-pytorch-with-nlp)
  - [Summary](#summary)
  - [Key Learnings](#key-learnings)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Dataset](#dataset)
  - [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction to HuggingFace 🤗

HuggingFace is an open-source platform for AI and machine learning that provides powerful tools and libraries designed to streamline the process of working with NLP models. This tutorial focuses on key functionalities of HuggingFace libraries such as `datasets`, `transformers`, and `evaluate`, with a PyTorch implementation of key artifacts.

### Summary

In the HuggingFace tutorial, we covered:

- **Datasets Library**: Efficient data handling and integration with PyTorch's DataLoader for seamless batching and processing.
- **Transformers Library**: Access to pre-trained models and tokenizers, and how to apply sampling techniques such as top-k and top-p (nucleus) sampling.
- **Evaluate Library**: Standardized metrics for text generation tasks and model evaluation.
- **Ease of Training**: Flexible training loops with HuggingFace's Trainer API and custom training approaches.
- **Multilingual and Multimodal Support**: HuggingFace’s tools for cross-lingual NLP and multimodal research.

### Key Learnings

- **Efficiency and Abstraction**: HuggingFace abstracts low-level details to help focus on model applications.
- **Custom Training**: Flexibility in designing training loops and optimizations.
- **Seamless Hardware Integration**: Easy switching between CPU, GPU, and other accelerators.
- **Multilingual and Multimodal Research**: Support for multilingual and multimodal models for interdisciplinary research.

## Introduction to PyTorch with NLP

PyTorch is a dynamic deep learning framework, highly favored for its flexibility and ease of use in research and production environments. This tutorial provides a comprehensive guide to PyTorch, with a focus on building NLP models for multi-class text classification tasks.

### Summary

In the PyTorch tutorial, we covered:

- **Tensors**: Basic operations and the importance of PyTorch's dynamic computation graph.
- **Data Preparation**: Loading, tokenizing, padding, and truncating sequences, as well as building a vocabulary.
- **Model Implementation**: A feedforward neural network for text classification using PyTorch, with a focus on embedding layers and training loops.
- **Model Evaluation**: Common metrics like accuracy, precision, recall, and F1 score, along with visualization through a confusion matrix.
- **Inference**: Predicting sentiments for new text inputs using the trained model.

### Key Learnings

- **PyTorch Flexibility**: Dynamic computational graphs make PyTorch a powerful tool for developing NLP models with variable-length input data.
- **Data Preprocessing**: Proper tokenization, padding, and truncation are essential for effective model training.
- **Model Training and Evaluation**: Training neural networks in PyTorch requires careful design and application of evaluation metrics to ensure good performance.
- **Model Inference**: Embeddings and softmax are key components in predicting accurate outcomes during inference.

## Getting Started

To get started with the tutorials, follow the instructions below.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/nlp-tutorials-huggingface-pytorch.git
   cd nlp-tutorials-huggingface-pytorch

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

### Dataset
Make sure to download and prepare the datasets as needed for the tutorials. Instructions for data preprocessing and setup are provided in the respective notebooks.

### Usage
To run the notebooks, simply open them in Jupyter:

```bash
jupyter notebook
```

You can explore both tutorials by running:
- huggingface_tutorial.ipynb
- pytorch_nlp_tutorial.ipynb


### Contributing

Contributions to these tutorials are welcome! Please open an issue or submit a pull request with your changes. We encourage sharing new examples, improvements, or bug fixes.
