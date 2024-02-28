# 🧠 Perceptron Classifier for Binary Numbers

A simple neural network consisting of two single-layer perceptrons to classify 21-digit binary numbers into three categories based on the count of 'ones' present in the number. This project implements the fundamental concepts of perceptron-based classification, including weight initialization, prediction, training, and plotting decision boundaries.

<p align="center">
  <a href="cover.png" target="_blank">
    <img src="cover.png" alt="Perceptron Classifier" width="400">
    </a>
</p>

---

<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [🧠 Perceptron Classifier for Binary Numbers](#-perceptron-classifier-for-binary-numbers)
  - [📖 Overview](#-overview)
  - [🌟 Features](#-features)
  - [💻 Technologies Used](#-technologies-used)
  - [🛠 Installation and Setup](#-installation-and-setup)
  - [🚀 Usage](#-usage)
  - [👥 Contributing](#-contributing)
  - [📄 License](#-license)
  - [🎉 Acknowledgments](#-acknowledgments)

<!-- /code_chunk_output -->

---

## 📖 Overview

This project implements a simple neural network consisting of perceptrons to classify 21-digit binary numbers into three categories based on the count of 'ones' present in the number. The categories are:

1. Numbers with more than 15 ones. ✅
2. Numbers with less than 15 ones. ❌
3. All other numbers. 🔄

The implementation demonstrates the fundamental concepts of perceptron-based classification, including weight initialization, prediction, training, and plotting decision boundaries. This project is part of my software engineering portfolio, showcasing my understanding of machine learning algorithms and my ability to implement them from scratch.

## 🌟 Features

- **Perceptron Training**: Trains two separate perceptrons to classify the binary numbers into the specified categories.
- **Prediction**: Predicts the category of a new 21-digit binary number.
- **Visualization**: Plots the decision boundaries of the perceptrons and the distribution of the binary numbers based on the classification.
- **Interactive GUI**: A simple Tkinter GUI for easy interaction with the perceptron classifier.

## 💻 Technologies Used

- Python 3
- NumPy for numerical operations
- Matplotlib for plotting
- Tkinter for the GUI
- Scikit-learn for PCA (Principal Component Analysis) used in plotting decision boundaries

## 🛠 Installation and Setup

Ensure you have Python 3.x installed on your system. You can download Python [here](https://www.python.org/downloads/).

Clone the repository to your local machine:

```bash
git clone https://github.com/Dor-sketch/PerceptualBinaryClassifier/git
```

Navigate to the cloned repository:

```bash
cd perceptron-binary-classifier
```

Install the required Python packages:

```bash
pip install numpy matplotlib scikit-learn
```

## 🚀 Usage

To run the program and launch the GUI, execute the following command in the terminal:

```bash
python perceptron.py
```

<p align="center">
  <img src="perceptron_gui.png" alt="Perceptron GUI" width="400">
</p>

In the GUI, you can:

- Enter a 21-digit binary number to predict its category.

- Train the perceptron models with generated binary numbers.

- Visualize the decision boundaries and the distribution of binary numbers.

<p align="center">
  <img src="boundary.png" alt="Decision Boundaries" width="600">
</p>

## 👥 Contributing

Contributions to this project are welcome! Please feel free to fork the repository, make your changes, and submit a pull request.

## 📄 License

This project is open-sourced under the MIT License. See the LICENSE file for more details.

## 🎉 Acknowledgments

This problem is an implementation of a problem presented in the course "**CA 20581 Biological Computation**" 2024a, taken at *the Open University of Israel*.
