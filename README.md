# Ecommerce Book Recommendation Model

📎 **[View Final Presentation Slides (PDF)](https://github.com/hyunji0618/Ecommerce-Book-Recommendation-Model/blob/main/Book_Recommendation_Slides.pdf)**

---

## 📚 Overview
This project presents a **personalized book recommendation engine** for an e-commerce bookstore, combining **customer segmentation via K-Means clustering** with tailored genre-based book recommendations. The system enhances the shopping experience and drives re-engagement through targeted promotions and behavioral insights.

## 👩‍💻 Team Members
- Amy Kim
- Sam Fisher
- Sally Shen
- Heath Liao
- Suma Ragi

## 🧠 Methodology

### 1️⃣ Customer Segmentation
- Applied **K-Means clustering** on RFM (Recency, Frequency, Monetary) data
- Identified 5 customer segments: Champions, Loyal, At Risk, Promising, Hibernating
- Optimized cluster count using the **Elbow Method**
- Removed outliers (e.g., bulk buyers) for cleaner segmentation

### 2️⃣ Book Recommendation Engine
- Mapped customer preferences to **book genres** using historical behavior
- Used a **books dataset from Kaggle** (Goodreads Best Books) to generate personalized suggestions
- Built a simple **collaborative filtering system** using **cosine similarity**

### 3️⃣ Strategy & Front-End Demo
- Designed promotional strategies for each customer segment
- Proposed a front-end interface where users receive dynamic, personalized messages and book suggestions
- Demonstrated potential **$650,000 revenue uplift** through segmentation and targeted offers

## 📊 Data Sources
- Customer purchase data (simulated, includes RFM features)
- Book dataset from Kaggle: [Goodreads Best Books](https://www.kaggle.com/datasets/meetnaren/goodreads-best-books)

## 🛠 Tech Stack
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- K-Means Clustering, Cosine Similarity

