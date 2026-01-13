# AI-Driven Product Recommendation System  
### Module E – AI for Market Trend Analysis

## 📌 Project Overview
This project implements an end-to-end AI-driven product recommendation and
customer analytics system inspired by real-world e-commerce platforms such as Amazon.

The system analyzes large-scale product data, simulates customer behavior,
segments users using marketing analytics techniques, and generates personalized
product recommendations.

The primary objective of this project is to demonstrate the complete AI project
lifecycle, including data understanding, exploratory analysis, modeling,
evaluation, and documentation.

---

## 🎯 Key Features
- Large-scale data processing (1.1M+ Amazon products)
- Exploratory Data Analysis (Market Trend Analysis)
- Synthetic customer and transaction simulation (100,000 users)
- RFM-based customer segmentation
- Cohort analysis for customer retention trends
- Hybrid recommendation system:
  - Popularity-based recommendations
  - Category-based personalization
  - Upselling for high-value customers
- Explainable and interpretable logic (no black-box models)

---

## 📂 Dataset
**Amazon Products Dataset (2023)**  
Source: Kaggle  
🔗 https://www.kaggle.com/datasets/lokeshparab/amazon-products-dataset

> ⚠️ Note:  
> Due to GitHub file size limitations, raw dataset files are not uploaded to this
> repository. The dataset must be downloaded separately from Kaggle.

---

## 🧠 Methodology
The project follows a structured AI workflow:

1. Data Loading & Cleaning  
2. Exploratory Data Analysis (EDA)  
3. Synthetic User & Purchase History Generation  
4. RFM Analysis & Customer Segmentation  
5. Cohort Analysis (Retention Trends)  
6. Hybrid Recommendation System  
7. Ethical Considerations & Future Scope  

All steps are implemented and explained in a **single Jupyter Notebook**, which
serves as the primary evaluation artifact.

---

## 🗂️ Project Structure
amazon-recommendation-project/
│
├── notebook/
│   └── amazon_recommendation_system.ipynb
│
├── data/
│   └── raw/   (not uploaded – contains Kaggle CSV files)
│
├── README.md
└── .gitignore
---

## ▶️ How to Run the Project (VS Code – Local)

1. Clone the repository: git clone https://github.com//amazon-recommendation-project.git
2. Download the dataset from Kaggle and place all CSV files inside:data/raw/
3. Open the project folder in **VS Code**
4. Open the notebook:notebook/amazon_recommendation_system.ipynb
5. Run the notebook **top to bottom** using Python 3

---

## ⚖️ Ethical Considerations
- No real user data is used
- All customer data is synthetically generated to preserve privacy
- Recommendations may reflect popularity bias
- The system is built strictly for academic and analytical purposes

---

## 🚀 Future Enhancements
- Integration of real user interaction data
- NLP-based sentiment analysis on product reviews
- Collaborative filtering or deep learning-based recommender models
- Interactive dashboard using Streamlit or similar tools

---

## 📌 Course Information
**Module:** AI Applications – Module E  
**Project Type:** Individual Open Project  
**Focus Area:** AI for Market Trend Analysis

---

## ✅ Author
**Name:** G R Shankavi Varsha
**Institution:** IIT Ropar (Minor in AI)