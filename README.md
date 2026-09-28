# Deep Learning Coursework & Architectures (PyTorch)

A curated collection of end-to-end Deep Learning implementations developed during the **MSc in Artificial Intelligence at Università della Svizzera italiana (USI)**.  
The repository covers foundational optimization algorithms, computer vision pipelines, recurrent sequence modeling for NLP, and combinatorial optimization via Transformer architectures.

---

## 🚀 Projects Overview

| # | Topic | Architecture / Paradigm | Key Libraries | Highlight / Result |
| :---: | :--- | :--- | :--- | :--- |
| **01** | **Optimization & Polynomial Regression** | Linear Model, Custom Gradient Descent | `torch`, `numpy`, `matplotlib` | Step-by-step convergence tracking & parameter recovery under noisy signals. |
| **02** | **Image Classification on CIFAR-10** | Convolutional Neural Network (CNN) | `torch`, `torchvision` | End-to-end vision pipeline: channel-wise normalization, data augmentation, and confusion tracking across 10 classes. |
| **03** | **Sentiment Analysis on IMDb** | Bidirectional LSTM + Pretrained GloVe | `torch`, `datasets`, `re` | Two-phase training (frozen embeddings + fine-tuning) reaching **~89.8% Test Accuracy**. |
| **04** | **Heuristic TSP Solver** | Transformer (Pre-LayerNorm, Autoregressive) | `torch`, `networkx` | Autoregressive decoding with causal/greedy masking, outperforming baseline heuristics (**< 5% gap** to optimal). |

---

## 📂 Repository Structure

```text
├── 01-polynomial-regression/
│   └── polynomial_regression_gd.ipynb
├── 02-cnn-cifar10/
│   └── cifar10_cnn_classification.ipynb
├── 03-lstm-sentiment-analysis/
│   └── imdb_bilstm_glove.ipynb
├── 04-transformers-tsp/
│   └── tsp_transformer_heuristic.ipynb
├── .gitignore
├── requirements.txt
└── README.md
