# Spam Email Classifier

This project demonstrates how to build a spam email classifier using the Naive Bayes algorithm. The dataset contains email texts and their corresponding labels (spam or not spam). The steps include data preprocessing, vectorization, model training, and evaluation.

## Prerequisites

Ensure you have the following Python packages installed:

- numpy
- pandas
- nltk
- scikit-learn

You can install these packages using pip:

```bash
pip install numpy pandas nltk scikit-learn
```

## Dataset

The dataset used is `emails.csv`, which contains the following columns:
- `text`: The email content.
- `spam`: The label indicating whether the email is spam (1) or not (0).

## Steps

### 1. Data Loading and Initial Exploration

Load the dataset and perform initial exploration to understand its structure and content.

### 2. Data Cleaning

Remove duplicate entries and check for missing values.

### 3. Text Preprocessing

Define a function to process the text by removing punctuation and stopwords.

### 4. Feature Extraction

Convert the text data into a matrix of token counts using `CountVectorizer`.

### 5. Train-Test Split

Split the data into training and testing sets (80% training, 20% testing).

### 6. Model Training

Create and train the Naive Bayes classifier on the training data.

### 7. Model Evaluation

Evaluate the model on both training and testing data.

## Results

The classifier achieved high accuracy on both the training and testing data, indicating its effectiveness in detecting spam emails.

### Example Output

Training Data Evaluation:
- Precision, recall, F1-score, support, confusion matrix, and accuracy.

Testing Data Evaluation:
- Precision, recall, F1-score, support, confusion matrix, and accuracy.

## Conclusion

The Naive Bayes classifier performed well in classifying emails as spam or not spam. Further improvements could be made by exploring different feature extraction techniques and tuning the model's hyperparameters.

---
