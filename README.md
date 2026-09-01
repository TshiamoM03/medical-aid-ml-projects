# Medical Aid Data Analytics Projects
The work is based on a fictional South African medical aid provider seeking to use data analytics and machine learning to improve business decision-making and customer outcomes. Publicly available (syntehtic) datasets from Kaggle and scraped Google reviews were used to simulate real-world business scenarios.

Each notebook follows a data analytics workflow including:
- Exploratory data analysis (statistical analysis and visualisation)
- Data cleaning and preprocessing
- Feature engineering and selection
- Hyperparameter tuning
- ML Model training and testing
- Model evaluation and performance analysis

**Technologies:** Jupyter Notebook, Python, Pandas, Numpy, Scikit-learn, NLTK, Matplotlib, Seaborn

---

## Project 1. Medical Aid Charge Prediction
- **Business Scenario:** A medical aid provider wants to better understand how demographic, lifestyle, and geographic factors influence healthcare costs in order to develop more tailored pricing strategies.
- **Techniques:** Linear Regression, hyperparameter tuning (randomised search cv), regression performance evaluation
- **Dataset:** Kaggle Medical Cost Personal Datasets
- **Code:** [med_aid_regression.ipynb](med_aid_regression.ipynb)

## Project 2. Cancer Risk Prediction
- **Business Scenario:** To improve the efficiency of processing critical illness (dreaded disease) benefits, the medical aid provider wants to identify customers who may require cancer-related benefits more quickly.
- **Techniques:** Random Forest Classifier (and Balanced RFC), cross validation, hyperparameter tuning, classification performance evaluation
- **Dataset:** Kaggle Cancer Risk Factors Dataset
- **Code:** [med_aid_classification.ipynb](med_aid_classification.ipynb)

## Project 3. Natural Language Processing - Text Modelling & Sentiment Analysis
- **Business Scenario:** The medical aid provider has observed an increase in negative online customer reviews and wants to better understand customer experiences. Scraped medical aid reviews were analysed using natural language processing to identify common discussion topics through topic modelling and to determine overall customer sentiment using sentiment analysis.
- **Technique:**
  - *Topic Modelling:* text preprocessing, TF-IDF/ Count Vectorisation, LDA
  - *Sentiment Analysis:* Multinomial Naive Bayes, Logistic Regression, hyperparameter tuning, model evaluation
- **Dataset:** medical_aid_google-reviews.csv
- **Code:** [med_aid_nlp.ipynb](med_aid_nlp.ipynb)

---

## Technologies
- Python
- Jupyter Notebook
- Pandas, Numpy, Scikit-learn, NLTK, Matplotlib, Seaborn
