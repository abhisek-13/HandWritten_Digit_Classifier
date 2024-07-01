# Handwritten Digit Prediction Model

This repository contains a Convolutional Neural Network (CNN) based model for handwritten digit recognition with 98% accuracy. The project is implemented in a Jupyter Notebook (`.ipynb` file), and the code is designed to be easy to understand, modify, and use for further development, including creating your webpage using this model.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project aims to classify handwritten digits (0-9) using a Convolutional Neural Network (CNN). The model is trained on the MNIST dataset and achieves an accuracy of 98%. The code is provided in a single Jupyter Notebook, making it easy to follow and adapt.

## Dataset

The model is trained on the [MNIST dataset](http://yann.lecun.com/exdb/mnist/), which contains 60,000 training images and 10,000 test images of handwritten digits.

## Model Architecture

The CNN model used in this project consists of the following layers:

1. Convolutional Layer
2. Pooling Layer
3. Dropout Layer
4. Dense Layer

The model is built using the TensorFlow and Keras libraries.

## Installation

You need to have Python and Jupyter Notebook installed to run the code. You can install the required libraries using the following command:

```bash
pip install -r requirements.txt
```
The requirements.txt file should include the following dependencies:

- numpy
- pandas
- matplotlib
- tensorflow
- keras
## Usage
1. Clone the repository:
```bash
git clone https://github.com/abhisek-13/HandWritten_Digit_Classifier.git
cd HandWritten_Digit_Classifier
```
2. Open the Hand_Written_digit_Recognition.ipynb file and run all the cells to train the model and see the results.

## Results
The model achieves an accuracy of 98% on the MNIST test dataset. Below is a sample of predictions made by the model:

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request if you have any ideas or improvements. Please ensure your changes are well-documented and tested.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
