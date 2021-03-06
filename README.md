# MLP-FarsiDigits-HodaDataset

A multilayer perceptron (MLP) is a class of feedforward artificial neural network (ANN). The term MLP is used ambiguously, sometimes loosely to any feedforward ANN, sometimes strictly to refer to networks composed of multiple layers of perceptrons (with threshold activation). Multilayer perceptrons are sometimes colloquially referred to as "vanilla" neural networks, especially when they have a single hidden layer.

An MLP consists of at least three layers of nodes: an input layer, a hidden layer and an output layer. Except for the input nodes, each node is a neuron that uses a nonlinear activation function. MLP utilizes a supervised learning technique called backpropagation for training. Its multiple layers and non-linear activation distinguish MLP from a linear perceptron. It can distinguish data that is not linearly separable.

Here, I classify Farsi digits by using the [Hoda Farsi Digit Dataset](https://github.com/amir-saniyan/HodaDatasetReader).

<img src="https://github.com/mahsawz/MLP-FarsiDigits-HodaDataset/blob/main/HodaFarsiDigits-image.png" width="250" height="150">

One sample of this dataset is:

<img src="https://github.com/mahsawz/MLP-FarsiDigits-HodaDataset/blob/main/sample.png" width="250" height="150">

I design an MLP by using Keras, and train it on Hoda dataset. Also, I calculate Precision, Recall, F1-score, and Accuracy metrics that you can see below in detail.

<img src="https://github.com/mahsawz/MLP-FarsiDigits-HodaDataset/blob/main/classification-report.png" width="300" height="250">
