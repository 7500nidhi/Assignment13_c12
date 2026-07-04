# Assignment 13: Text Generation Using LSTM

# Overview
This Assignment implements a text generation model using a Long Short-Term Memory (LSTM) neural network with TensorFlow and Keras. The model is trained on a text dataset to learn language patterns and predict the next word in a sequence.

# Objective
The objective of this assignment is to build an LSTM-based text generation model that learns from a text dataset and generates text by predicting one word at a time.

# Dataset
- **Dataset:** Alice's Adventures in Wonderland
- **Source:** Project Gutenberg
- **Format:** Plain text (.txt)

# Technologies Used 
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib

#  Workflow
1. Load the text dataset.
2. Preprocess the text (cleaning and tokenization).
3. Generate input sequences.
4. Apply sequence padding.
5. Build an LSTM model.
6. Train the model.
7. Generate text using the trained model.
8. Save the trained model.

# Model Architecture
The model consists of:
- Embedding Layer
- LSTM Layer
- Dense Output Layer with Softmax activation

# Results
- Successfully trained an LSTM text generation model.
- Training accuracy improved over multiple epochs.
- Training loss decreased during training.
- Generated text by predicting one word at a time.

# How to Run

1. Clone the repository.

```bash
git clone https://github.com/7500nidhi/Assignment13_c12.git
```

2. Install the required libraries.

```bash
pip install tensorflow numpy matplotlib
```

3. Open the notebook.

```bash
jupyter notebook Assignment13_c12.ipynb
```

4. Run all cells to train the model and generate text.
