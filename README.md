# CIFAR-10 Image Classification

This project demonstrates image classification on the CIFAR-10 dataset using two different neural networks implemented with **PyTorch**:

1. **MLP (Multi-Layer Perceptron)** – 3 fully-connected layers.
2. **SimpleCNN** – 3 convolutional blocks followed by linear layers.

## Setup

```bash
# Create virtual environment (optional)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Run

Follow steps in notebook

The script will automatically download the CIFAR-10 dataset, split it into training, validation, and test sets, then train and evaluate each model, printing accuracy metrics to the console.

Both models default to training for 15 epochs. Adjust hyper-parameters at the top of `main.py` as desired. 