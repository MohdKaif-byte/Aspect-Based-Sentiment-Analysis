# Aspect-Based Sentiment Analysis on TripAdvisor Reviews

## Project Overview
This project performs **aspect-based sentiment analysis** on TripAdvisor reviews to uncover:  
- Key aspects that customers discuss  
- Words associated with positive and negative experiences  
- Reasons why certain comments are neutral  

The analysis helps businesses understand what customers **like, dislike, and how to improve their services**.

---

## Dataset
- **Source:** Kaggle – TripAdvisor Hotel Reviews  
- **Contents:** User reviews with ratings and comments  
- **Features used:** Review text, ratings, aspects extracted from text  

---

## Objective
- Identify the **most talked-about aspects** of hotels  
- Extract **top positive and negative words** associated with each aspect  
- Rank **top 10 liked and disliked aspects**  
- Train a **classification model** to explain neutral comments  

---

## Approach

### 1. Data Cleaning & Preprocessing
- Remove stopwords, punctuation, and irrelevant content  
- Tokenization and lemmatization of words  

### 2. Aspect Extraction
- Identify key aspects (e.g., room, service, location)  
- Count frequency and find top aspects  

### 3. Sentiment Analysis
- Map words to positive/negative sentiment  
- Find top positive and negative words for each aspect  

### 4. Neutral Comment Classification
- Train a machine learning model to explain why a comment is neutral  

---

## Results / Insights
- Clear identification of **top 10 most discussed aspects**  
- Top positive and negative words associated with each aspect  
- Model successfully explains **why certain reviews are neutral**  
- Provides **actionable insights** for businesses to improve services  

---

## Files in Repository
- `Aspect_Based_Sentiment_Analysis_Mikus_Kaif_2.0.ipynb` → Jupyter notebook with full code and analysis  
- `data/` → Dataset  
- `test_data/` → Unseen data for testing  
- `Aspect_Based_Sentiment_Analysis_Mikus_Kaif_2.0.html` → Visualizations, code, and outputs  

---

## Technologies Used
- **Python:** Pandas, NumPy, Scikit-learn, NLTK, SpaCy  
- **Jupyter Notebook**  
- **Visualization libraries:** Matplotlib, Seaborn  

---

## How to Run
1. Clone the repository:  
```bash
git clone https://github.com/MohdKaif-byte/Aspect-Based-Sentiment-Analysis.git

2.Install dependencies:

pip install -r requirements.

3. Open the notebook in Jupyter:

jupyter notebook Aspect_Based_Sentiment_Analysis.ipynb




