# NLP Projects Portfolio 🧠

This repository is a collection of hands-on projects in Natural Language Processing, demonstrating a range of tasks from fundamental text classification to advanced transformer-based models. Each project highlights a specific NLP technique and its application, with a focus on real-world implementations and actionable results.

---

### 1. Sentiment Analysis 🎬
* **Objective:** Classify movie reviews as positive or negative.
* **Methodology:** Preprocessed, tokenized, and vectorized a dataset of movie reviews.
* **Key Achievements:**
    * Implemented and compared **Logistic Regression** and **Naive Bayes** classification pipelines.
    * Visualized the most frequent words across sentiment classes to identify key polarity indicators.

---

### 2. News Classification 📰
* **Objective:** Perform multiclass classification to categorize news articles.
* **Methodology:** Cleaned and preprocessed the dataset, followed by vectorization.
* **Key Achievements:**
    * Built baseline classification with **Logistic Regression** and boosted performance using a custom **Neural Network**.
    * Plotted word frequency distributions per category to analyze topic separation.

---

### 3. Fake News Detection 💯
* **Objective:** Distinguish between true and fake news articles.
* **Methodology:** Preprocessed and feature-engineered datasets before training.
* **Key Achievements:**
    * Developed an end-to-end detection pipeline using **Logistic Regression**.
    * Generated comparative word visualizations to highlight linguistic differences between real and fabricated articles.

---

### 4. Named Entity Recognition (NER) 🏷️
* **Objective:** Extract named entities from a news articles dataset.
* **Methodology:** Implemented both rule-based and model-based entity recognition pipelines.
* **Key Achievements:**
    * Benchmarked heuristic rule-based pattern matching against pre-trained transformer pipelines.
    * Built custom visualizers to render extracted entities inline across documents.

---

### 5. Topic Modeling 📖
* **Objective:** Discover dominant latent themes within a news articles dataset.
* **Methodology:** Tokenized the preprocessed dataset and applied unsupervised clustering algorithms.
* **Key Achievements:**
    * Extracted semantic themes using both probabilistic (**LDA**) and matrix factorization (**NMF**) techniques.
    * Generated word clouds illustrating topic-term distributions for distinct clusters.

---

### 6. Question Answering ✅
* **Objective:** Build an extractive QA system using transformers on the SQuAD dataset.
* **Methodology:** Implemented and fine-tuned a pre-trained **DistilBERT** architecture.
* **Key Achievements:**
    * Fine-tuned DistilBERT on context-question pairs to extract precise answer spans.
    * Evaluated zero-shot baseline performance against the domain-adapted model.

---

### 7. Text Summarization 📝
* **Objective:** Generate concise summaries of news articles.
* **Methodology:** Utilized a pre-trained **Pegasus** transformer model.
* **Key Achievements:**
    * Implemented both extractive heuristic baselines and abstractive sequence-to-sequence generation.
    * Fine-tuned the Pegasus model to adapt text abstraction to news reporting styles.

---

### 8. Resume Screening 🎯
* **Objective:** Automatically match candidate resumes against target job descriptions.
* **Methodology:** Employed dense vector similarity scoring using semantic embeddings.
* **Key Achievements:**
    * Built an automated screening pipeline powered by **Sentence Transformers**.
    * Added multi-format file parsing and support for both batch and single-document processing workflows.
