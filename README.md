# Text Classifier - Recurrent Neural Network

This repository demonstrates a Recurrent Neural Network (RNN) implementation for sentiment classification using natural language data. The project covers text preprocessing, model training, and evaluation, and includes a user-friendly prediction pipeline for real-world testing.

## Why Use RNN?
Recurrent Neural Networks (RNNs) are powerful for processing sequential data like text. Their architecture enables:
- Capturing temporal and contextual dependencies in sequences.
- Handling variable-length input sequences.
- Application in tasks like sentiment analysis, text generation, and language modeling.

## Features
- **Data Preprocessing**:
  - Text cleaning: HTML tag removal, stopword filtering, stemming.
  - Tokenization and padding for uniform input size.
- **Model Architecture**:
  - Word embeddings using an `Embedding` layer.
  - Sequential data processing with a `SimpleRNN` layer.
  - Dropout for regularization and Dense layers for classification.
- **Training Pipeline**:
  - Early stopping to optimize model performance.
  - Visualization of training metrics for insight.
- **Prediction**:
  - Easy-to-use interface for predicting sentiment from custom text inputs.

## Example Prediction

```python
Enter your text: "I love this product!"
Predicted Sentiment: Positive
``` 
