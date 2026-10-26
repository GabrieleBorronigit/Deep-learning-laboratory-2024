# Deep learning laboratory 2024

Exercises done during the Deep Learning course of prof. S. Carrazza at the University of Milan, with TensorFlow/Keras. Each notebook covers one topic, from the basic building blocks to CNNs and recurrent networks.

| Notebook | Content |
|---|---|
| [01_tensorflow_basics](01_tensorflow_basics.ipynb) | MLP with TensorFlow primitives and with Keras, linear fit with a manual SGD loop (`tf.GradientTape`) |
| [02_regression_and_classification](02_regression_and_classification.ipynb) | 1D regression (linear model vs dense network), Fashion-MNIST classification |
| [03_cnn_classification_and_localization](03_cnn_classification_and_localization.ipynb) | CIFAR-10 with a dense network vs a CNN, CNN with two heads that classifies an MNIST digit and predicts its bounding box |
| [04_iris_and_lstm](04_iris_and_lstm.ipynb) | Iris classification with early stopping, LSTM for a temperature time series |

## Usage

```
pip install -r requirements.txt
jupyter notebook
```

Fashion-MNIST and CIFAR-10 are downloaded directly by Keras. The other datasets (`data.dat` for the regression, `data/` for the localization and the `.npy` files for the LSTM) were provided during the course (see [scarrazza/DL2025](https://github.com/scarrazza/DL2025)) and have to be put in the same folder of the notebooks.
