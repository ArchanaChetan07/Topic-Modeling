# Topic Modeling with LSA, NMF, and LDA

This project explores topic modeling using unsupervised machine learning techniques such as **Latent Semantic Analysis (LSA)**,

**Non-negative Matrix Factorization (NMF)**, and **Latent Dirichlet Allocation (LDA)**.

It applies these models to a cleaned and preprocessed text dataset, leveraging vectorization methods like **TF-IDF** and **CountVectorizer** to extract topics.
---
## Techniques Used
-  Text Cleaning (stopword removal, lemmatization)
-  Vectorization: `CountVectorizer` & `TfidfVectorizer`
-  Topic Models:
  - LSA using `TruncatedSVD`
  - NMF using `sklearn.decomposition.NMF`
  - LDA using `LatentDirichletAllocation`
-  Visualization:
  - Word distributions per topic
  - pyLDAvis interactive visualization
---
