# SENTIMENT-ANALYSIS

COMPANY - CODTECH IT SOLUTION

NAME - SOHAM MAHAJAN

INTERNID - CT04DY2129

DOMAIN - DATA ANALYST

DURATION - 4 WEEKS

MENTOR - NEELA SANTOSH

# Sentiment Analysis using NLP 📝

**Project Type:** Internship / Beginner Project  
**Language & Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, WordCloud  
**Model Used:** Multinomial Naive Bayes (Text Classification)

---

## 🔹 Project Overview

This project demonstrates **Sentiment Analysis** on textual data using **Natural Language Processing (NLP)** techniques. The goal is to classify text (e.g., product reviews) into **positive, negative, or neutral** sentiments.  

Key steps include:

- Data creation & preprocessing  
- Text feature extraction using **TF-IDF**  
- Model training using **Naive Bayes**  
- Evaluation and interpretation of results  
- Insights on top words contributing to each sentiment  

---

## 🔹 Dataset


| Text                                | Sentiment |
|------------------------------------|-----------|
| I love this product                 | positive  |
| This is the worst experience        | negative  |
| Absolutely fantastic service        | positive  |
| I hate waiting in long queues       | negative  |
| Not bad, could be better            | neutral   |
| Excellent quality and fast delivery | positive  |
| Very disappointing and rude staff   | negative  |
| I am happy with my purchase         | positive  |
| Worst product ever                  | negative  |
| Totally satisfied and recommended  | positive  |


---

## 🔹 Key Steps in Notebook

1. **Import Libraries**  
   Libraries used include `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, and `wordcloud`.

2. **Data Creation & Exploration**  
   Dataset is created in code. Explored sentiment distribution using count plots.

3. **Word Cloud Visualization**  
   Generated word clouds to visualize frequently used words in **positive and negative** reviews.

4. **Data Preprocessing**  
   - Convert text to lowercase  
   - Remove noise if needed (optional for larger datasets)

5. **Feature Extraction**  
   - Convert text into **numerical features** using `TF-IDF Vectorizer`.

6. **Train/Test Split**  
   - 80% data for training, 20% for testing.

7. **Model Implementation**  
   - **Multinomial Naive Bayes** used for classification.

8. **Predictions & Evaluation**  
   - Accuracy, confusion matrix, and classification report generated.  

9. **Feature Insights**  
   - Top words contributing to **positive, negative, and neutral** sentiment identified.

---

## 🔹 Results

- **Accuracy:** ~100% 
- **Top words per sentiment:**  

| Sentiment | Top Words |
|-----------|-----------|
| Positive  | ['excellent', 'love', 'absolutely', 'fast', 'satisfied'] |
| Negative  | ['worst', 'hate', 'disappointing', 'rude', 'waiting'] |
| Neutral   | ['bad', 'better', 'not'] |

- Word clouds visually show the most frequent words for **positive** and **negative** sentiments.

---

##  🔹 OUTPUT



