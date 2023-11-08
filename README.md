# SSL Autoencoder MNIST

Using self-supervised learning to pre-train an autoencoder on the MNIST dataset and fine-tuning the encoder using 1% of labeled data with a classifier output layer. Comparing the accuracy with a pure supervised classifier model trained on 1% of the training data.

## Requirements
- Python 3.11
```bash
pip install -r requirements.txt
```

## Notebooks
Notebook containing the code and results for the autoencoder and classifier is located in the `notebooks` folder.

## Models
The trained models are located in the `models` folder. The autoencoder model is named `autoencoder.h5` and the classifier model is named `supervised_model.h5`.
