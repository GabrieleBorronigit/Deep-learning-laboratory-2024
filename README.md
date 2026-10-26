# Deep learning laboratory 2024

Deep learning exercises with TensorFlow/Keras, done during the Deep Learning course of prof. S. Carrazza (notebooks 01-04) and the Numerical Simulation Laboratory of prof. D.E. Galli (05-06) at the University of Milan. Each notebook covers one topic, from the basic building blocks to CNNs and recurrent networks.

| Notebook | Content |
|---|---|
| [01_tensorflow_basics](01_tensorflow_basics.ipynb) | MLP with TensorFlow primitives and with Keras, linear fit with a manual SGD loop (`tf.GradientTape`) |
| [02_regression_and_classification](02_regression_and_classification.ipynb) | 1D regression (linear model vs dense network), Fashion-MNIST classification |
| [03_cnn_classification_and_localization](03_cnn_classification_and_localization.ipynb) | CIFAR-10 with a dense network vs a CNN, CNN with two heads that classifies an MNIST digit and predicts its bounding box |
| [04_iris_and_lstm](04_iris_and_lstm.ipynb) | Iris classification with early stopping, LSTM for a temperature time series |
| [05_regression_with_neural_networks](05_regression_with_neural_networks.ipynb) | Dense networks fitting a line, a cubic polynomial and sin(x²+y²), and their behaviour outside the training interval |
| [06_mnist_dense_vs_cnn](06_mnist_dense_vs_cnn.ipynb) | MNIST with a dense network and with a CNN, then tested on digits written by me (`digits/`) |

## Usage

```
pip install -r requirements.txt
jupyter notebook
```

MNIST, Fashion-MNIST and CIFAR-10 are downloaded directly by Keras. The other datasets (`data.dat` for the regression, `data/` for the localization and the `.npy` files for the LSTM) were provided during the course (see [scarrazza/DL2025](https://github.com/scarrazza/DL2025)) and have to be put in the same folder of the notebooks.
