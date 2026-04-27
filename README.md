# 🕵️‍♂️ Fake News Detection Engine

This repository features a robust Natural Language Processing (NLP) solution designed to classify and analyze news authenticity. The project covers the full end-to-end data pipeline, from raw text heuristic cleaning to statistical modeling and latent topic extraction.

---

### 🚀 Tech Stack
* **Language:** Python 3.12
* **NLP & Text Processing:** NLTK, Spacy, Regular Expressions (Regex)
* **Vectorization:** Scikit-Learn (TF-IDF, Bag of Words)
* **Topic Modeling:** Gensim (LDA, LSA)
* **Data Visualization:** Seaborn, Matplotlib

---

### 🧠 Architecture & Methodology

#### 1. Preprocessing & Data Cleaning
* **Heuristic Cleaning:** Normalized text using **Regex** to remove noise, special characters, and HTML artifacts.
* **Tokenization:** Applied stopword removal and lemmatization to reduce vocabulary dimensionality.
* **Pipeline:** Efficient string reconstruction using optimized join operations for vectorization readiness.

#### 2. Feature Engineering & Topic Modeling
* **TF-IDF & BoW:** Engineered weighted numerical vectors to represent semantic importance.
* **LSA (Latent Semantic Analysis):** Applied SVD for dimensionality reduction and latent relationship identification.
* **LDA (Latent Dirichlet Allocation):** Implemented probabilistic modeling to discover underlying themes within the datasets.
* **Coherence Score ($C_v$):** Used to quantitatively validate the interpretability and quality of the generated topics.

#### 3. Classification Models
The project evaluates and benchmarks two core algorithms:
* **Logistic Regression:** Used as a high-performance baseline for linear decision boundaries.
* **SVM (Support Vector Machines):** Implemented to capture complex hyperplanes in the high-dimensional word-vector space.

---

### 📊 Visualization & Insights
The notebook includes detailed visual analysis of:
* Distribution of Unigrams, Bigramas, and Trigrams.
* Named Entity Recognition (NER) frequency analysis.
* Coherence curves for optimal topic $K$ selection.

---

### 🛠️ Installation & Usage
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/fake-news-detector.git](https://github.com/your-username/fake-news-detector.git)
