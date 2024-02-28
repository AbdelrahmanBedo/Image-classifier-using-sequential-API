# Fashion MNIST Classification with TensorFlow

This repository contains code for a simple image classification task using TensorFlow with the Fashion MNIST dataset. Fashion MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes.

## Requirements

- Python 3.x
- TensorFlow
- Matplotlib
- Pandas
- NumPy

## Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo.git
```

2. Navigate to the repository directory:

```bash
cd your-repo
```

3. Run the script:

```bash
python fashion_mnist_classification.py
```

## Description

The script `fashion_mnist_classification.py` loads the Fashion MNIST dataset using TensorFlow's built-in dataset functionality. It preprocesses the data by splitting it into training, validation, and test sets, normalizing the pixel values, and defines the class names for the labels. Then, a simple neural network model is built using TensorFlow's Keras API. The model architecture consists of a flatten layer followed by two dense layers with ReLU activation, and an output layer with softmax activation. After compiling the model, it's trained on the training data and evaluated on the test data. Finally, the predictions are made on a sample of test images and compared with the actual labels.


## Acknowledgements

- This project uses the Fashion MNIST dataset provided by TensorFlow.
- TensorFlow and Keras for deep learning functionalities.
- Matplotlib for visualization.
- Pandas for data analysis.
- NumPy for numerical computing.
