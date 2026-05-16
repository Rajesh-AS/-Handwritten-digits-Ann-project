# Handwritten Digits Classification using ANN

This project demonstrates a simple Artificial Neural Network (ANN) built with TensorFlow and Keras to classify handwritten digits from the classic **MNIST dataset**. 

## Overview
The model uses a single Dense layer to take flattened 28x28 pixel images (784 inputs) and output probabilities for the 10 digit classes (0-9). Despite its simplicity, the model achieves around **92.5% accuracy** on the test dataset after just 5 epochs of training.

## Technologies Used
- **Python 3**
- **TensorFlow / Keras** (Deep Learning framework)
- **NumPy** (Numerical operations and array manipulations)
- **Matplotlib** (Data visualization)
- **Jupyter Notebook** (Interactive development environment)

## Model Architecture
- **Input:** 784 features (flattened 28x28 grayscale images, normalized to values between 0 and 1)
- **Hidden/Output Layer:** 1 Dense layer with 10 neurons (one for each digit 0-9) and a `sigmoid` activation function.
- **Optimizer:** `adam`
- **Loss Function:** `sparse_categorical_crossentropy`

## Dataset
The MNIST dataset is loaded directly via `keras.datasets.mnist`. It consists of:
- 60,000 training images 
- 10,000 testing images

## Usage
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Rajesh-AS/-Handwritten-digits-Ann-project.git
   ```
2. Navigate into the project directory:
   ```bash
   cd -Handwritten-digits-Ann-project
   ```
3. Install the required dependencies (preferably in a virtual environment):
   ```bash
   pip install tensorflow numpy matplotlib jupyter
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook model/model.ipynb
   ```
5. Run the notebook cells sequentially to load the data, visualize it, train the model, and make predictions.
