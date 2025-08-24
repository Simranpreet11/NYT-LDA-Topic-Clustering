# 📰 Topic Modelling on New York Times Articles

## 🎯 Objective

The goal of this project is to automatically group *New York Times* articles into meaningful topics using machine learning.
This helps in:

* Recommending articles to readers based on interests
* Organizing and categorizing large collections of articles
* Finding patterns and trends in news coverage
* Supporting advertisers and editors with better insights

---

## 🔎 Approach

### Dataset

* Used a subset of around **500,000 articles** from *The New York Times*
* Important fields: **Title**, **Abstract**, and **Lead Paragraph**

### Preprocessing

Steps taken to prepare the data for modeling:

1. Removed missing values and cleaned unwanted characters
2. Tokenized the text (split into words)
3. Lemmatized words (reduced to base form, e.g., “running” → “run”)
4. Removed stopwords (common words like “the”, “and”)
5. Converted text to numerical format using **TF-IDF**

### Models Used

* **Latent Dirichlet Allocation (LDA)** – a probabilistic model for discovering hidden topics
* **Non-Negative Matrix Factorization (NMF)** – a matrix decomposition technique for topic discovery

### Evaluation

* Tested both LDA and NMF with different numbers of topics
* Looked at top keywords in each topic to check interpretability
* Used **pyLDAvis** to visualize topic clusters and separations

---

## ✅ Observations & Results

* **LDA with 6 topics** produced the clearest and most meaningful results

* Identified topics matched real-world categories, such as:

  1. **Business & Economics** – markets, companies, finance
  2. **Arts, Media & Culture** – reviews, music, photography, cultural stories
  3. **Current Events & Global Affairs** – COVID-19, politics, international news
  4. **Sports & Lifestyle** – games, players, fashion, lifestyle
  5. **Politics & Governance** – elections, government, policies
  6. **Education & Social Issues** – schools, families, crime, society

* LDA topics were more **interpretable and distinct** compared to NMF

* Visualizations confirmed good separation between topics

---

## 📌 Conclusion

* The **LDA model with 6 topics** is the best choice for this dataset
* It creates clear, human-readable topics that align with news categories
* The project shows how topic modeling can be applied to:

  * Personalizing news recommendations
  * Automatically tagging and organizing content
  * Understanding audience interests
  * Supporting data-driven editorial decisions

---

Would you like me to now turn this into a **ready-to-use `README.md` file** and give you the download link?
