# 🕵️‍♂️ Fake News Detection Engine

Este repositório contém uma solução de Processamento de Linguagem Natural (NLP) desenvolvida para classificar e analisar notícias, identificando padrões de desinformação. O projeto abrange desde o pré-processamento de texto até a modelagem estatística e extração de tópicos latentes.

---

### 🚀 Tecnologias Utilizadas
* **Linguagem:** Python 3.12
* **Processamento de Texto:** NLTK, Spacy, Regex
* **Vetorização e Modelagem:** Scikit-Learn (TF-IDF, Bag of Words)
* **Extração de Tópicos:** Gensim (LDA, LSA)
* **Visualização de Dados:** Seaborn, Matplotlib

---

### 🧠 Arquitetura e Metodologia

#### 1. Pré-processamento e Limpeza (Data Cleaning)
* Normalização de texto com **Expressões Regulares** para remoção de ruídos e caracteres especiais.
* Tokenização e remoção de *stopwords*.
* Reconstrução de strings limpas para vetorização.

#### 2. Engenharia de Features e Extração de Tópicos
* **TF-IDF & Bag of Words:** Transformação de texto em vetores numéricos ponderados.
* **LSA (Latent Semantic Analysis):** Redução de dimensionalidade para encontrar relações semânticas latentes.
* **LDA (Latent Dirichlet Allocation):** Modelagem probabilística de tópicos para identificar os principais temas nos datasets.
* **Coherence Score ($C_v$):** Utilizado para validar a interpretabilidade dos tópicos gerados.

#### 3. Modelos de Classificação
O projeto compara a performance de dois algoritmos fundamentais:
* **Logistic Regression:** Utilizado como baseline de alta performance e interpretabilidade.
* **SVM (Support Vector Machines):** Aplicado para capturar hiperplanos de separação mais complexos no espaço vetorial das palavras.

---

### 📊 Visualizações e Insights
O notebook inclui análises visuais de:
* Distribuição de Unigramas e Bigramas.
* Gráficos de Entidades Nomeadas (NER) mais frequentes.
* Curvas de Coerência para definição do número ideal de tópicos.

---

### 🛠️ Como Instalar e Rodar
1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/fake-news-detector.git](https://github.com/seu-usuario/fake-news-detector.git)
