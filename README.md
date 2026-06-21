# 42AI Technical Test — Fashion-MNIST Classification

MLP classifier built with PyTorch trained on the Fashion-MNIST dataset.

## Setup

This project uses **pyenv** with a virtual environment for Python version management.

```bash
pyenv install 3.12.3
pyenv virtualenv 3.12.3 42AI
pyenv activate 42AI
pip install -r requirements.txt
```

> Note: `scikit-learn` is not part of the base PyTorch stack but was added for evaluation metrics (classification report, confusion matrix).

## Usage

Open the notebook `42AI-Technical-Test.ipynb` and run all cells in order.