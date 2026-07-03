# DecodeLabs_Task4

## Project Overview

This repository contains my **Task 4: Movie Review Sentiment Analysis** completed as part of the **DecodeLabs Data Science Internship**.

The project builds a Natural Language Processing (NLP) pipeline that automatically classifies movie reviews as **Positive** or **Negative**. It performs text preprocessing, feature extraction using **TF-IDF**, and sentiment classification using machine learning models trained on the **NLTK Movie Reviews** dataset.

---

## Repository Structure

```text
DecodeLabs_Task4/
│
├── DecodeLabsTask4.ipynb      # Jupyter Notebook containing the complete project
└── README.md                  # Project documentation
```

---

## Dataset

* **Dataset:** NLTK Movie Reviews Corpus
* **Source:** Built-in dataset provided by NLTK
* **Classes:**

  * Positive Reviews
  * Negative Reviews

---

## Technologies Used

* Python
* NLTK
* NumPy
* Scikit-learn
* Jupyter Notebook

---

## Features

* Automatic loading of the NLTK Movie Reviews dataset
* Text preprocessing and cleaning
* Stopword removal with preserved negation words
* POS-guided lemmatization using WordNet
* TF-IDF vectorization with unigrams and bigrams
* Machine learning-based sentiment classification
* Model evaluation using classification metrics

---

## Project Workflow

### 1. Dataset Loading

* Loads positive and negative movie reviews from the NLTK Movie Reviews corpus.

### 2. Text Preprocessing

* Converts text into tokens.
* Removes unnecessary stopwords while preserving negation words.
* Applies POS tagging.
* Performs WordNet lemmatization for better text normalization.

### 3. Feature Extraction

* Converts text into numerical features using **TF-IDF Vectorization**.
* Uses both **unigrams** and **bigrams** to capture contextual information.

### 4. Model Training

* Splits the dataset into training and testing sets.
* Trains machine learning classifiers for sentiment prediction.

### 5. Model Evaluation

* Measures model performance using:

  * Accuracy Score
  * Classification Report
* Predicts whether reviews are **Positive** or **Negative**.

---

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/MahnoorDataScientist/DecodeLabs_Task4.git
```

### 2. Open the project folder

```bash
cd DecodeLabs_Task4
```

### 3. Install the required libraries

```bash
pip install numpy nltk scikit-learn
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open and run

```text
DecodeLabsTask4.ipynb
```

---

## Output

Running the notebook generates:

* Cleaned and preprocessed movie reviews
* TF-IDF feature vectors
* Trained sentiment classification model
* Accuracy score
* Classification report
* Predicted sentiment labels for movie reviews

---

## Learning Outcomes

Through this project, I learned how to:

* Build an end-to-end NLP pipeline
* Perform text preprocessing and cleaning
* Apply POS tagging and lemmatization
* Extract text features using TF-IDF
* Train machine learning models for sentiment analysis
* Evaluate classification models using performance metrics

---

## Author

**Mahnoor Ramzan**

**GitHub:** https://github.com/MahnoorDataScientist

---

## If you found this project helpful, consider giving it a star on GitHub!

