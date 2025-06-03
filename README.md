# SequenceClassification with PyTorch
Colab notebook performing sequence classification using esm2_t36. 
This repository contains a PyTorch training loop for classifying protein residue embeddings into functional classes. 

# Features
Custom training loop with gradient accumulation and learning rate scheduling

Optional AMP integration for faster training on compatible GPUs

Validation and testing loops with accuracy, precision, recall, and F1 score metrics

Model checkpoint saving based on best validation F1 score

Clear example of embedding-based classification (compatible with pretrained protein language models)

Usage
Clone this repository:

```

git clone https://github.com/yourusername/protein-residue-classification.git
cd protein-residue-classification
```
Install dependencies (recommended to use a virtual environment):

```

pip install -r requirements.txt
```

Run the training notebook or script:

Colab notebook: Open protein-residue-classification.ipynb to run interactively.

Script: Run train.py after updating dataset and model paths.


