# 🍽 Zomato Restaurant Sentiment Analysis & Clustering

## 📌 Project Overview

This project performs Sentiment Analysis and Restaurant Segmentation on Zomato restaurant data to generate business insights for customers and companies.

The analysis combines restaurant metadata and customer reviews to understand customer satisfaction, pricing trends, cuisine performance, and reviewer behavior.

---

## 🎯 Objectives

- Perform NLP-based Sentiment Analysis on customer reviews
- Analyze cost vs rating trends
- Identify top-performing cuisines
- Segment restaurants using K-Means Clustering
- Identify influential reviewers
- Provide actionable business insights

---

## 📂 Dataset Description

Two datasets were used:

1. **Restaurant Metadata**
   - Name
   - Cost
   - Cuisines
   - Collections
   - Timings

2. **Restaurant Reviews**
   - Restaurant
   - Reviewer
   - Review
   - Rating
   - Time
   - Pictures

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TextBlob (NLP)

---

## 🧠 Methodology

### 1️⃣ Data Cleaning
- Removed null values
- Converted rating and cost into numeric format
- Merged metadata and review datasets

### 2️⃣ Sentiment Analysis
- Used TextBlob to calculate sentiment polarity
- Classified reviews into:
  - Positive
  - Negative
  - Neutral

### 3️⃣ Exploratory Data Analysis
- Sentiment distribution visualization
- Cost vs Rating scatter analysis
- Cuisine performance analysis
- Reviewer activity analysis

### 4️⃣ Clustering
- Applied K-Means clustering
- Features used:
  - Rating
  - Cost
- Segmented restaurants into 4 categories

---

## 📊 Key Insights

- Majority of reviews are positive.
- Mid-range restaurants provide the best value for money.
- Premium restaurants show mixed sentiment due to high expectations.
- Certain cuisines consistently achieve higher ratings.
- A small percentage of reviewers contribute most reviews.
- Restaurants can be segmented into:
  - Premium
  - Budget-friendly
  - High-performing
  - Underperforming

---

## 🚀 Business Impact

### For Customers:
- Identify best restaurants based on sentiment
- Compare value for money
- Discover hidden gems

### For Businesses:
- Improve low-performing segments
- Optimize pricing strategy
- Target high-performing cuisines
- Identify influential reviewers

---

## 📈 Future Improvements

- Implement BERT-based advanced sentiment analysis
- Include vote count and engagement in clustering
- Deploy interactive dashboard using Power BI or Streamlit
- Automate model retraining

---

## 📎 How to Run

1. Clone the repository:
