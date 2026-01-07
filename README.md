# 🔍 Cross-Domain Sentiment Analysis

This repository demonstrates a comprehensive **cross-domain sentiment analysis** project covering multiple datasets, preprocessing pipelines, model development, cross-domain evaluation, and visualization of results.

The goal of this project is to evaluate how well sentiment classification models trained on one domain generalize to other domains.

---

## 📚 Project Overview

This project works with sentiment datasets from different domains, including:

- Movie reviews (IMDB)
- Social media posts
- Twitter airline sentiment
- Twitter training dataset
- Consumer complaint narratives

We explore:
- Dataset-specific preprocessing strategies
- TF-IDF–based feature extraction
- Logistic Regression–based classifiers
- Cross-domain model transferability
- Performance comparison through visualizations

---

## 📁 Repository Structure

```text
.
├── Preprocessing/
│   ├── imdb_preprocessing.ipynb
│   ├── socialmedia_preprocessing.ipynb
│   ├── twitter_us_airline_preprocessing.ipynb
│   ├── twitter_training_preprocessing.ipynb
│   └── consumer_complaints_preprocessing.ipynb
│
├── clean_data/
│   ├── IMDB-Dataset_cleaned.csv
│   ├── socialmedia_sentiment_cleaned.csv
│   ├── twitter_us_airline_cleaned.csv
│   ├── twitter_training_cleaned.csv
│   └── consumer_complaints_cleaned.csv
│
├── plots/
│   └── (Saved plots such as confusion matrices, accuracy comparisons)
│
├── model_development.ipynb
├── cross_domain_analysis_with_visualization.ipynb
└── README.md
```
---

##  Workflow Description

### 🔹 Data Preprocessing

Each dataset is cleaned and preprocessed independently to handle:

* Text normalization
* Noise removal
* Label consistency
* Domain-specific characteristics

All preprocessing notebooks are located in the `Preprocessing/` folder, and the cleaned datasets are saved to `clean_data/`.

---

### 🔹 Model Development

The `model_development.ipynb` notebook performs:

* TF-IDF feature extraction
* Model training using Logistic Regression
* Saving trained models and vectorizers for reuse

Each dataset is treated as a separate training domain.

---

### 🔹 Cross-Domain Evaluation

The `cross_domain_analysis_with_visualization.ipynb` notebook:

* Loads trained models and vectorizers
* Evaluates them on datasets from other domains
* Computes accuracy, confusion matrices, and comparison metrics
* Generates visualizations for performance analysis

All plots are saved in the `plots/` directory.

---

## ▶️ How to Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/<your-username>/Cross-Domain-Sentiment-Analysis.git
   cd Cross-Domain-Sentiment-Analysis
   ```

2. **Preprocess datasets**

   * Open notebooks inside the `Preprocessing/` folder
   * Run each notebook to generate cleaned datasets

3. **Train models**

   * Open and run `model_development.ipynb`

4. **Run cross-domain analysis**

   * Open and run `cross_domain_analysis_with_visualization.ipynb`
   * Generated plots will be saved automatically in `plots/`

---

## 📊 Outputs

* Cleaned datasets for each domain
* Trained sentiment classification models
* Cross-domain performance metrics
* Visualizations including:
* Confusion matrices
* Accuracy comparison plots

---

## 🔧 Requirements

* Python 3.x
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook or Google Colab

---

## 👥 Team Members

* **Arpitha Thippeswamy**
* **Anti Li**

---


