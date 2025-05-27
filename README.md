# NLP-Model
## 🧠 Sentiment Analysis on Swiggy Reviews Using RNN and SpaCy
 This project performs sentiment analysis on customer reviews from Swiggy, focusing on preprocessing natural language text and classifying ratings using a Recurrent Neural Network (RNN).

## 📌 Features
- Text preprocessing using SpaCy for tokenization, lemmatization, POS tagging.

- Vectorization using TF-IDF.

- Handling class imbalance with SMOTE (Synthetic Minority Over-sampling Technique).

- Sentiment classification using Simple RNN with TensorFlow/Keras.

## 🗂️ Dataset
Swiggy30.xlsx: Contains customer review descriptions and ratings.

Processed to derive:

review_description ➝ cleaned, lemmatized, and tagged.

rating ➝ converted into binary labels (positive/negative).

## ⚙️ Workflow
#### 1. Load and Preprocess Data

- Lemmatization, stopword removal, and POS tagging using SpaCy.

### 2. Feature Engineering

- Convert text into TF-IDF vectors.

- Apply SMOTE for class balance.

### 3. Modeling

- Simple RNN built using TensorFlow/Keras.

- Training and evaluation on resampled data.

### 4. Evaluation

- Accuracy metric used for performance evaluation.

## 📊 Visualizations
- Rating distribution histogram.

- POS-tagged tokens viewable in preprocessing steps.

## 🔮 Future Work
- Improve model with LSTM/GRU.

- Hyperparameter tuning.

- Deploy as a sentiment analysis API.
