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

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your_username/RNN_Text_Classifier.git
   cd RNN_Text_Classifier
   ```
2. Usage
  - Data Preparation:
        Place training and validation datasets in the data/ directory with appropriate CSV formatting.
        Update file paths in the notebook if necessary.

    - Run the Model:
        Open the notebook:

        ```jupyter notebook NLP_with_RNN.ipynb```
        Execute cells to preprocess data, train the model, and evaluate performance.
      
  - Make Predictions:
Use the interactive prediction cell in the notebook to classify text sentiment.




## Example Prediction

```python
Enter your text: "I love this product!"
Predicted Sentiment: Positive
``` 
