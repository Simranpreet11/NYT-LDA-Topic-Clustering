# 📰 Topic Modelling on New York Times Articles

## 📌 Objective

The purpose of this project is to develop a **topic classification system** for *New York Times* articles. By applying topic modeling techniques, the project automatically groups articles into meaningful categories.

This supports applications such as:

* Personalized content recommendations
* Automated tagging & categorization
* Audience segmentation
* Trend discovery & analysis
* Advertiser alignment

---

## 🔎 Approach

### 📂 Dataset

* Subset of \~500k *New York Times* articles
* Features used: **Title, Abstract, Lead Paragraph**

### ⚙️ Preprocessing

* Data cleaning (null handling, irrelevant character removal)
* Tokenization & Lemmatization
* Stopword removal
* Feature extraction using **TF-IDF**

### 🧠 Models

* **Latent Dirichlet Allocation (LDA)**
* **Non-Negative Matrix Factorization (NMF)**

### 📊 Evaluation

* Compared models with varying numbers of topics
* Analyzed topic keywords for interpretability
* Used **pyLDAvis** for visualization and cluster separation

---

##
