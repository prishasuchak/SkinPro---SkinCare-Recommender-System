# 🧴 SkinPro – Intelligent Skincare Recommendation System  

SkinPro is a **machine learning–based skincare recommendation system** that helps users find the best products based on their **skin type, concerns, and preferences**.  
It uses **Sentence-BERT embeddings** and **cosine similarity** to match user queries with the most relevant skincare products.  

---

## 🚀 Features
- Extracts **product type** automatically from product names.  
- Combines **skin type + concern + product type** into a unified representation.  
- Uses **Sentence-BERT (all-MiniLM-L6-v2)** for semantic embeddings.  
- Provides **top-N product recommendations** with product URLs.  
- Evaluates system quality using **Mean Reciprocal Rank (MRR)** and **Precision@5**.  

---

## 🛠️ Tech Stack
- **Python 3**
- **pandas** – data handling  
- **scikit-learn** – cosine similarity  
- **sentence-transformers** – embeddings (SBERT)  
- **numpy** – numerical ops  
- **tabulate** – formatted console output  

---

## 📂 Dataset
The system uses a dataset (`skinpro.csv`) with the following columns:  
- `Product` – product name  
- `Skin type` – suitable skin type (oily, dry, sensitive, etc.)  
- `Concern` – skincare concerns (acne, pigmentation, anti-aging, etc.)  
- `product_url` – purchase link  

---




   


