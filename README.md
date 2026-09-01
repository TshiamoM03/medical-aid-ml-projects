# Medical Aid Data Analytics Projects
The work is based on a fictional South African medical aid provider seeking to use data analytics and machine learning to improve business decision-making and customer outcomes. Publicly available (syntehtic) datasets from Kaggle and scraped Google reviews were used to simulate real-world business scenarios.

Each notebook follows a data analytics workflow including:
- Exploratory data analysis (statistical analysis and visualisation)
- Data cleaning and preprocessing
- Feature engineering and selection
- Hyperparameter tuning
- ML Model training and testing
- Model evaluation and performance analysis

---

## Project 1. Medical Aid Charges Prediction
- **Business Scenario:** A medical aid provider wants to better understand how demographic, lifestyle, and geographic factors influence healthcare costs in order to develop more tailored pricing strategies.
- **Techniques:** Linear Regression, hyperparameter tuning (randomised search cv), regression performance evaluation
- **Dataset:** Kaggle Medical Cost Personal Datasets

## Project 2. Cancer Risk Prediction
- **Business Scenario:** To improve the efficiency of processing critical illness (dreaded disease) benefits, the medical aid provider wants to identify customers who may require cancer-related benefits more quickly.
- **Techniques:** Random Forest Classifier (and Balanced RFC), cross validation, hyperparameter tuning, classification performance evaluation
- **Dataset:** Kaggle Cancer Risk Factors Dataset

## Project 3. Natural Language Processing - Text Modelling & Sentiment Analysis
- **Business Scenario:** The medical aid provider has observed an increase in negative online customer reviews and wants to better understand customer experiences. Scraped medical aid reviews were analysed using natural language processing to identify common discussion topics through topic modelling and to determine overall customer sentiment using sentiment analysis.
- **Technique:**
  - *Topic Modelling:* text preprocessing, TF-IDF/ Count Vectorisation, LDA
  - *Sentiment Analysis:* Multinomial Naive Bayes, Logistic Regression, hyperparameter tuning, model evaluation
- **Dataset:** medical_aid_google-reviews.csv

---

## Technologies
- Python
- Jupyter Notebook
- Pandas, Numpy, Scikit-learn, NLTK, Matplotlib, Seaborn

---
**Note:** the business scenarios are simulated. All analysis was done on publicly available Kaggle datasets and publicly accessible online customer reviews.
