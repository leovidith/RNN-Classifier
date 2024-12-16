# Text Classifier - Recurrent Neural Network

## Project Objective:
To develop and deliver a robust, user-friendly **Recurrent Neural Network (RNN)** for text sentiment classification through iterative sprints.

---

### Features:
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

---

### Why Use RNN?
Recurrent Neural Networks (RNNs) are powerful for processing sequential data like text. Their architecture enables:
- Capturing temporal and contextual dependencies in sequences.
- Handling variable-length input sequences.
- Application in tasks like sentiment analysis, text generation, and language modeling.

---

### Agile Sprint Overview:

#### **Sprint 1: Data Collection and Preprocessing**
- Collect and validate the text dataset.
- Perform preprocessing steps (e.g., cleaning, tokenization, padding).
- Deliverable: Preprocessed dataset ready for modeling.

#### **Sprint 2: Model Architecture Design**
- Build the RNN architecture with Embedding, SimpleRNN, Dropout, and Dense layers.
- Deliverable: RNN model blueprint ready for training.

#### **Sprint 3: Model Training and Optimization**
- Train the model using early stopping and visualize training metrics.
- Optimize hyperparameters based on performance.
- Deliverable: Trained RNN model.

#### **Sprint 4: User Prediction Interface Development**
- Create an interface for real-time sentiment prediction.
- Validate predictions with real-world test cases.
- Deliverable: Functional prediction interface.

#### **Sprint 5: Deployment and Documentation**
- Deploy the trained model and interface on the platform.
- Prepare user-friendly guides and collect user feedback for improvements.
- Deliverable: Deployed system with complete documentation.

---

### Example Prediction:

```python
Enter your text: "I love this product!"
Predicted Sentiment: Positive
```

---

This Agile implementation ensures a structured pathway for delivering a high-quality RNN-based text classifier aligned with both technical excellence and user expectations.

