# NLP-Project
# 🏨 TripAdvisor Hotel Reviews – NLP & Sentiment Analysis

This project analyzes hotel reviews from TripAdvisor using Natural Language Processing (NLP).  
The goal was to clean and process customer reviews, understand their sentiment, and compare it with the actual ratings they gave.

---

## 📊 Dataset

The dataset contains hotel reviews with two columns — **Review** (text) and **Rating** (1 to 5).  
Most reviews are positive, which makes sense since people usually post when they’ve had a great experience.

---

## ⚙️ What I Did

1. **Data Cleaning & Preprocessing**  
   - Removed stopwords, punctuation, and special characters  
   - Lemmatized words using **spaCy**  
   - Converted all text to lowercase  

2. **Feature Engineering**  
   - Calculated word count and character count for each review  
   - Extracted the most frequent words, bigrams, and trigrams using `CountVectorizer`

3. **Sentiment Analysis**  
   - Used **VADER Sentiment Analyzer** to get sentiment scores for each review  
   - Classified them as *Positive*, *Negative*, or *Neutral* based on polarity scores  

4. **Comparison with Actual Ratings**  
   - Converted numeric ratings (1–5) into sentiment categories  
   - Compared model predictions with actual user sentiments to check how well they align  

---
