
```markdown
# Cross-Domain Sentiment Analysis

This repository demonstrates a comprehensive cross-domain sentiment analysis project that covers multiple datasets, preprocessing, model development, cross-domain evaluation, and visualization.

## Project Structure

```
.
├── Preprocessing/
│   ├── imdb_preprocessing.ipynb
│   ├── socialmedia_preprocessing.ipynb
│   ├── twitter_us_airline_preprocessing.ipynb
│   ├── twitter_training_preprocessing.ipynb
│   └── consumer_complaints_preprocessing.ipynb
├── clean_data/
│   ├── IMDB-Dataset_cleaned.csv(.gz)
│   ├── socialmedia_sentiment_cleaned.csv
│   ├── twitter_us_airline_cleaned.csv
│   ├── twitter_training_cleaned.csv
│   └── consumer_complaints_cleaned.csv
├── plots/
│   └── (All saved plots, e.g., confusion matrices, accuracy comparisons)
├── model_development.ipynb
├── cross_domain_analysis_with_visualization.ipynb
└── README.md
```

## Description

- **Preprocessing/**: Contains individual notebooks that clean and preprocess each dataset.
- **clean_data/**: Contains the cleaned and preprocessed datasets.
- **plots/**: Contains all visualizations generated during cross-domain analysis.
- **model_development.ipynb**: Notebook for training models on each dataset.
- **cross_domain_analysis_with_visualization.ipynb**: Notebook for evaluating model performance across datasets and visualizing the results.

## Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/<YourUsername>/Cross-Domain-Sentiment-Analysis.git
   cd Cross-Domain-Sentiment-Analysis
   ```

2. **Data Preprocessing:**
   - Open each notebook in the `Preprocessing/` folder (e.g., `imdb_preprocessing.ipynb`) using Jupyter Notebook or Google Colab.
   - Run the cells to clean and preprocess the corresponding dataset.
   - Cleaned data will be saved in the `clean_data/` folder.

3. **Model Development:**
   - Open `model_development.ipynb` and run the notebook to:
     - Load the cleaned datasets.
     - Extract features using TF-IDF.
     - Train models (e.g., Logistic Regression).
     - Save trained models and vectorizers.

4. **Cross-Domain Analysis:**
   - Open `cross_domain_analysis_with_visualization.ipynb`.
   - The notebook loads saved models and vectorizers, applies them across different datasets, and generates performance metrics and visualizations.
   - All plots are saved in the `plots/` folder.

## Requirements

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook or Google Colab


## Author : Arpitha Thippeswamy 
Team Member : Anti Li

