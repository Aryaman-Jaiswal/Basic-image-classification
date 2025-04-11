# TensorFlow Beginner: Basic Image Classification

This project is designed for beginners to get started with image classification using TensorFlow and Keras. The goal is to create and train a neural network model that can accurately predict digits from hand-written images using the MNIST dataset.

## Project Structure

- **notebooks/**: Contains the Jupyter notebook `TensorFlow_Beginner_Basic_Image_Classification.ipynb`, which includes all the code and markdown explanations for the project.
- **images/**: Contains images used in the notebook to illustrate various concepts related to neural networks and the classification task.
  - `1_1.png`: Visual description of the problem of classifying hand-written digits.
  - `1_2.png`: Illustration of a single neuron in a neural network.
  - `1_3.png`: Representation of a single neuron with 784 features.
  - `1_4.png`: Depiction of a neural network with two hidden layers.
  - `1_5.png`: Visual representation of the linear sum and activation function.

## Setup Instructions

1. **Clone the repository**:
   ```
   git clone <repository-url>
   cd tensorflow-beginner-basic-image-classification
   ```

2. **Install required packages**:
   It is recommended to use a virtual environment. You can create one using `venv` or `conda`. Then, install the necessary packages:
   ```
   pip install tensorflow matplotlib
   ```

3. **Run the Jupyter Notebook**:
   Launch Jupyter Notebook in the project directory:
   ```
   jupyter notebook notebooks/TensorFlow_Beginner_Basic_Image_Classification.ipynb
   ```

## Usage Guidelines

- Follow the instructions in the notebook to understand the process of image classification.
- The notebook is structured into sections that cover:
  - Introduction to the problem
  - Exploration of the MNIST dataset
  - One-hot encoding of labels
  - Building and training a neural network
  - Evaluating model performance
  - Making predictions on test data

Feel free to modify the code and experiment with different neural network architectures or hyperparameters to improve model performance. Happy coding!