# Customer Feedback Analytics using NLP and Machine Learning
## A Case Study on IMDb Movie Reviews

![Python](https://img.shields.io/badge/Python-3.10-blue)
![NLP](https://img.shields.io/badge/NLP-Sentiment%20Analysis-green)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Logistic%20Regression-orange)

---

# Business Problem

Online platforms generate massive volumes of customer feedback every day, making it difficult for organizations to manually analyze user opinions and identify key drivers of customer satisfaction or dissatisfaction.

For movie production companies, streaming platforms, and entertainment businesses, understanding audience sentiment is critical for evaluating content performance, improving user experience, and making data-driven decisions.

This project leverages Natural Language Processing (NLP) and Machine Learning techniques to automatically classify movie reviews as positive or negative, enabling scalable sentiment monitoring and feedback analysis.

---

# Project Objective

The primary objective of this project is to develop an end-to-end sentiment analysis solution capable of extracting actionable insights from unstructured textual reviews.

The project focuses on:

- Transforming raw textual reviews into structured data.
- Identifying patterns associated with positive and negative sentiments.
- Exploring customer sentiment through text analytics techniques.
- Applying NLP preprocessing and feature engineering.
- Building machine learning models for sentiment classification.
- Comparing Bag of Words and TF-IDF vectorization techniques.

---

# Dataset Information

**Dataset:** IMDb Movie Reviews Dataset

**Source:** Kaggle

**Total Reviews:** 50,000

**Features:**

| Feature | Description |
|----------|-------------|
| review | Movie review text |
| sentiment | Positive / Negative |

Dataset contains an equal distribution of positive and negative reviews.

---

# Project Workflow

```text
Data Collection
        ↓
Data Understanding
        ↓
Text Cleaning
        ↓
Tokenization
        ↓
Stopword Removal
        ↓
Lemmatization
        ↓
Exploratory Text Analysis
        ↓
Word Frequency Analysis
        ↓
Word Cloud Analysis
        ↓
Bigram & Trigram Analysis
        ↓
Bag of Words Vectorization
        ↓
TF-IDF Vectorization
        ↓
Logistic Regression
        ↓
Model Evaluation
        ↓
Business Insights
```

---

# Text Preprocessing

The following NLP preprocessing techniques were applied:

- Lowercase Conversion
- HTML Tag Removal
- URL Removal
- Punctuation Removal
- Tokenization
- Stopword Removal
- Lemmatization

These steps helped improve text quality and reduce noise in the dataset.

---

# Exploratory Text Analysis

The project includes:

- Review Length Analysis
- Word Frequency Analysis
- Positive and Negative Word Clouds
- Bigram Analysis
- Trigram Analysis

These techniques help uncover common themes and linguistic patterns within customer reviews.

---

# Word Frequency Analysis
<img width="10736" height="4138" alt="Word_Frequency_for_Reviews" src="https://github.com/user-attachments/assets/18920dd3-48fc-40dc-a5d9-fc4f1354cf63" />

---

# Word Cloud Analysis

## Positive Reviews

<img width="7095" height="3759" alt="Word_Cloud-Positive_Reviews" src="https://github.com/user-attachments/assets/9330b433-bd77-4ade-8502-0a822f197783" />


## Negative Reviews

<img width="7095" height="3759" alt="Word_Cloud-Negative_Reviews" src="https://github.com/user-attachments/assets/c4153e98-829d-458d-b4c2-33b27cfb1443" />


---

# Bigram Analysis

## Positive Reviews

<img width="6507" height="3271" alt="positive_bigram_analysis" src="https://github.com/user-attachments/assets/ce6f75c4-fa5e-4d76-a6c0-dc67993421bd" />


## Negative Reviews

<img width="6507" height="3271" alt="negative_bigram_analysis" src="https://github.com/user-attachments/assets/6eb372e5-a1ae-4066-92d2-c96a570e4185" />


---

# Feature Engineering

Two vectorization techniques were evaluated:

## Bag of Words (BoW)

Converts text into numerical vectors using word occurrence frequencies.

## TF-IDF

Assigns higher importance to informative words and lower importance to common words.

---

# Model Building

A Logistic Regression classifier was trained using:

- Bag of Words Features
- TF-IDF Features

---

# Model Performance

| Model | Accuracy |
|---------|----------|
| Logistic Regression + Bag of Words | 86.34% |
| Logistic Regression + TF-IDF | 88.18% |

---

# Model Comparison

<img width="4118" height="2809" alt="model_comparison" src="https://github.com/user-attachments/assets/00ad1a86-7dfe-492a-86f8-b5a204c6d4b2" />


---

# Confusion Matrix (Best Model)

TF-IDF + Logistic Regression

<img width="3107" height="2347" alt="Confusion_Matrix_TF-IDF" src="https://github.com/user-attachments/assets/01f86623-7517-45d1-ae4e-26527f608018" />


---

# Key Findings

- Processed and analyzed 50,000 movie reviews.
- Applied NLP preprocessing techniques to clean and standardize text.
- Identified sentiment-specific vocabulary using word frequency and word cloud analysis.
- Performed bigram and trigram analysis to uncover common phrase patterns.
- Built sentiment classification models using Logistic Regression.
- TF-IDF outperformed Bag of Words by approximately 1.84 percentage points.
- Achieved 88.18% accuracy using TF-IDF vectorization.

---

# Business Impact

An automated sentiment analysis system can help organizations:

- Monitor customer satisfaction at scale.
- Analyze large volumes of feedback efficiently.
- Identify recurring customer concerns.
- Track audience perception of products and services.
- Support data-driven decision-making.

---

# Future Improvements

- Implement Random Forest and XGBoost models.
- Explore Deep Learning approaches such as LSTM and BERT.
- Perform Aspect-Based Sentiment Analysis.
- Deploy the solution using Streamlit.

---

# Conclusion

This project successfully applied Natural Language Processing and Machine Learning techniques to analyze 50,000 IMDb movie reviews and classify audience sentiment.

Among the evaluated approaches, TF-IDF combined with Logistic Regression achieved the best performance with an accuracy of 88.18%, outperforming the Bag of Words model.

The results demonstrate the importance of feature engineering in text classification tasks and highlight the effectiveness of NLP techniques for extracting meaningful insights from unstructured customer feedback.

---

## Author

**Deepak Pathak**
Data Analyst | SQL | Python | Power BI | NLP | Machine Learning
