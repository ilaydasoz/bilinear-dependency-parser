# Neural Dependency Parsing Mini Project

### Files

- `neural_dependency_parser.ipynb`: Jupyter Notebook containing the full implementation.
- `Neural_Dep_Report.pdf`: A short report summarizing the model, approach, and results.

### Overview

This mini project implements a simple **bilinear dependency parser** using **PyTorch**. The model is trained on the English UD EWT dataset to predict syntactic head words for each token in a sentence.

Key components include:
- A BiLSTM encoder for contextualized token embeddings
- MLP projections for heads and dependents
- A bilinear scoring layer for predicting dependency arcs

Training over 10 epochs led to a test accuracy of **81.62%**. This shows the effectiveness of the approach for learning dependencies.
