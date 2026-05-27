# MNIST Classification

Experiments in classifying handwritten digits from the MNIST dataset using
TensorFlow/Keras.

## Notebook

| File | Description |
| --- | --- |
| `MNIST_experiments.ipynb` | A Colab-style notebook that compares several models for MNIST digit classification. |

The notebook starts with a vanilla neural-network model and then explores:

- data augmentation
- deeper and very deep networks
- batch normalization
- dropout
- dropout combined with batch normalization
- convolutional neural networks
- inspection of classification errors

## How to run

Open `MNIST_experiments.ipynb` in Google Colab or Jupyter and run the cells from
top to bottom. The notebook uses TensorFlow 2.x, Keras, NumPy, and Matplotlib.
MNIST is loaded directly from `tf.keras.datasets`.
