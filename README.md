# 📊 ChatGPT Review Sentiment Analysis

## 📌 Project Overview

This project focuses on analyzing user reviews of ChatGPT to understand overall user sentiment, satisfaction levels, and frequently mentioned features.

Using Natural Language Processing (NLP) techniques, this project extracts meaningful insights from large-scale textual review data.

---

## 🎯 Problem Statement

Customer reviews contain valuable feedback. This project aims to answer:

- What is the overall sentiment of users towards ChatGPT?
- What features do users appreciate the most?
- What are the common complaints?
- How does sentiment evolve over time?

---

## 📂 Dataset Description

The dataset contains:

- `review_id` – Unique review identifier  
- `review` – User review text  
- `ratings` – Rating (1 to 5 stars)  
- `review_date` – Date of review  

📌 The dataset includes over **150,000+ reviews**, making it a large real-world dataset.

---

## 🛠 Tech Stack

- Python  
- Pandas  
- Matplotlib  
- TextBlob (NLP)  
- Collections  

---

## 🔄 Project Workflow

### 1️⃣ Data Loading
- Imported dataset using `pd.read_csv()`
- Inspected structure using `df.head()`

### 2️⃣ Data Cleaning
- Standardized column names (lowercase, underscore format)
- Checked and handled missing values
- Converted ratings to numeric format
- Converted review_date to datetime format

### 3️⃣ Sentiment Analysis
- Calculated **Polarity** (-1 to +1)
- Calculated **Subjectivity** (0 to 1)
- Categorized sentiment into:
  - Positive
  - Neutral
  - Negative

### 4️⃣ Exploratory Data Analysis (EDA)
- Sentiment distribution visualization
- Subjectivity score histogram
- Rating vs Sentiment comparison

### 5️⃣ Text Feature Extraction
- Filtered positive reviews
- Extracted most common positive phrases
- Filtered negative reviews
- Extracted most common negative phrases
- Used bigram & trigram techniques

### 6️⃣ Time-Based Analysis
- Review volume over time
- Sentiment trend over time

---

## 📊 Visualizations Included

- 📌 Distribution of Review Sentiments  
- 📌 Distribution of Sentiment Subjectivity Scores  
- 📌 Rating Distribution by Sentiment Category  
- 📌 Most Common Positive Phrases  
- 📌 Most Common Negative Phrases  
- 📌 Review Evolution Over Time  

---

## 🔍 Key Insights

- Majority of reviews are **Positive**
- Users frequently mention:
  - "very helpful"
  - "very useful"
  - "best app"
- Negative reviews commonly mention:
  - "wrong answer"
  - "bad app"
- Sentiment strongly aligns with star ratings
- Reviews are moderately subjective (mean ≈ 0.5)

---

## 📈 Business Impact

This analysis helps:

- Measure customer satisfaction
- Identify strengths and weaknesses
- Improve product performance
- Support data-driven decision making

---

## 🚀 Future Improvements

- Implement advanced NLP models (BERT, Transformers)
- Build interactive dashboards (Streamlit / Power BI)
- Apply topic modeling
- Perform deeper time-series analysis

---

⭐ If you found this project useful, feel free to give it a star!
