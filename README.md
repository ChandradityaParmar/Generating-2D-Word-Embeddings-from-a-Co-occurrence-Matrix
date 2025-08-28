# Word Embeddings from Co-occurrence Matrix using PCA
A Python script that demonstrates a fundamental Natural Language Processing (NLP) technique for generating and visualizing 2D word embeddings from a text corpus.

## 🌟 About The Project
This project provides a step-by-step implementation of a classic count-based method for creating word embeddings. It reads a small text corpus, builds a word co-occurrence matrix, and then uses Principal Component Analysis (PCA) to reduce the dimensionality of the matrix to 2D. The final 2D word vectors are then plotted to visually represent their semantic relationships.

This script is intended as an educational tool to understand the core concepts behind word vectorization and distributional semantics.

### ✨ Key Features:
* Text Preprocessing: Cleans and tokenizes raw text.

* Co-occurrence Matrix: Builds a matrix based on word proximity.

* Dimensionality Reduction: Uses PCA to reduce the matrix to 2D.

* Visualization: Plots the 2D word embeddings using Matplotlib.

🛠️ Built With
* Python 3

* NumPy

* Matplotlib

* Scikit-learn

## 🚀 Getting Started
To get a local copy up and running, follow these simple steps.

### Prerequisites
Ensure you have Python 3 and pip installed.

### Installation
1. Clone the repo

    ``` git clone [https://github.com/your-username/Word-Embeddings-PCA.git](https://github.com/your-username/Word-Embeddings-PCA.git) ```

2. Navigate to the project directory

    ``` cd Word-Embeddings-PCA ```

3. Install the required packages

    ``` pip install numpy matplotlib scikit-learn ```

## 📖 Usage
To run the script and generate the plot, execute the main Python file from your terminal:

    ``` python main.py ```

This will process the built-in corpus, perform the calculations, and display a Matplotlib window with the 2D plot of the word embeddings.
