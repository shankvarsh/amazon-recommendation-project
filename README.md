# AI-Driven Product Recommendation & Market Trend Analysis

## 📌 Project Overview
This project presents an end-to-end **AI-driven Product Recommendation System**
built using a large-scale Amazon Products dataset (2023).

The system combines:
- Market trend analysis
- Customer behavior modeling
- Sentiment analysis (NLP)
- Emotion-aware customer segmentation
- Personalized product recommendations

The project is designed as part of **Module E – AI Applications (Individual Open Project)**  
and demonstrates the **complete AI project lifecycle**, from data understanding to
actionable business insights.

---

## 🎯 Objectives
- Perform exploratory market trend analysis on Amazon product data
- Simulate realistic customer purchase behavior
- Segment customers using **RFM Analysis** and **Cohort Analysis**
- Integrate **sentiment analysis** to capture emotional feedback
- Build a **hybrid recommendation system** with upselling and cross-selling logic
- Ensure explainability, ethics, and reproducibility

---

## 📊 Dataset
- **Source:** Amazon Products Dataset (Kaggle, 2023)  
- **Link:** https://www.kaggle.com/datasets/lokeshparab/amazon-products-dataset  

### Dataset Characteristics
- ~1.1 million product records
- 140+ product category CSV files
- Includes product name, category, pricing, ratings, and review counts

⚠️ **Note:**  
The dataset does not include customer-level purchase history or review text.  
Therefore, **synthetic users, transactions, and review texts** were generated
for academic and analytical purposes.

Due to GitHub file size limits, **raw datasets are not uploaded** to this repository.

---

## 🧠 Project Methodology

### 1️⃣ Data Understanding & Cleaning
- Combined 140+ CSV files into a single dataset
- Removed irrelevant columns
- Converted prices and ratings to numeric format
- Handled missing values using business logic

### 2️⃣ Exploratory Data Analysis (Market Trends)
- Category-wise product distribution
- Price distribution analysis
- Ratings and popularity trends
- Identification of dominant product categories

### 3️⃣ Synthetic User & Transaction Generation
- Simulated **100,000 unique users**
- Generated **1,000,000 purchase transactions** for the year 2023
- Created realistic purchase dates, quantities, and spending behavior

### 4️⃣ RFM Analysis (Customer Segmentation)
Customers were segmented based on:
- **Recency** (days since last purchase)
- **Frequency** (number of purchases)
- **Monetary value** (total spend)

Segments include:
- Big Spenders
- Loyal Customers
- At-Risk Customers
- Regular Customers

### 5️⃣ Cohort Analysis
- Grouped users by first purchase month
- Analyzed retention trends over time
- Visualized customer retention using heatmaps

### 6️⃣ Sentiment Analysis (NLP)
- Generated synthetic review text based on ratings
- Applied **VADER Sentiment Analysis**
- Classified sentiment as Positive, Neutral, or Negative
- Analyzed sentiment trends across product categories

### 7️⃣ Emotional Loyalty Modeling (Novel Contribution)
A new **Emotional Loyalty Score** was introduced by combining:
- RFM scores
- Average sentiment score per user

This enabled identification of:
- Emotionally Loyal Customers
- High-Value but Unhappy Customers
- Emotionally Disengaged Customers

### 8️⃣ Recommendation System
A **hybrid recommendation engine** was built:
- New users → Popular products
- Returning users → Category-based recommendations
- Big spenders → Premium upsell recommendations
- Emotion-aware recommendations using sentiment + RFM

---

## 📈 Key Results
- Successfully processed over **1.1 million products**
- Generated **large-scale synthetic customer data**
- Identified meaningful customer segments and retention patterns
- Built a **sentiment-aware recommendation system**
- Provided explainable, business-ready insights

---

## ⚖️ Ethical Considerations
- No real user data was used; all customer data is synthetic
- Sentiment analysis is based on simulated review text
- Popularity and emotional bias are acknowledged and documented
- The system is intended strictly for academic and educational use

---

## 🚧 Limitations
- Synthetic data may not fully capture real-world intent
- Rule-based recommendation logic (no deep embeddings)
- No real-time user feedback loop
- Sentiment analysis does not capture sarcasm or complex language

---

## 🔮 Future Scope
- Integrate real transaction or clickstream data
- Apply collaborative filtering or deep learning models
- Use transformer-based sentiment models (BERT)
- Build interactive dashboards using Streamlit
- Explore reinforcement learning for dynamic recommendations

---

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **NLP:** VADER Sentiment Analysis
- **Environment:** VS Code, Jupyter Notebook
- **Version Control:** Git & GitHub

---

## 📁 Repository Structure
amazon-recommendation-project/

│

├── notebook/

│   └── amazon_recommendation_system.ipynb

│

├── data/

│   └── raw/   (ignored in GitHub)

│

├── README.md

└── .gitignore

---

## ✅ How to Run
1. Clone the repository
2. Download the dataset from Kaggle (link above)
3. Place CSV files inside `data/raw/`
4. Open `amazon_recommendation_system.ipynb`
5. Run all cells top-to-bottom

---

## 📌 Author
**Individual Academic Project**  
Module E – AI Applications  

---

## ⭐ Final Note
This project demonstrates how **AI, analytics, and NLP** can be combined
to build intelligent, explainable, and business-relevant systems,
even when working with incomplete real-world data.