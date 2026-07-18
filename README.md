#  Fake News Detection System

##  Project Overview
This project is a Fake News Detection System built using *Python, **Machine Learning, and **Streamlit. It predicts whether a news article is **Real* or *Fake* using a Logistic Regression model with TF-IDF text vectorization.

##  Features
- Detects fake and real news articles
- Text preprocessing using NLTK
- TF-IDF Vectorization
- Logistic Regression classifier
- Interactive Streamlit web application

##  Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Streamlit

##  Dataset
- train.csv

##  How to Run
1. Clone the repository
2. Install the required libraries:
   bash
   pip install streamlit pandas numpy scikit-learn nltk
   
3. Run the application:
   bash
   streamlit run streamlitapp.py
   

## Model
- Algorithm: Logistic Regression
- Feature Extraction: TF-IDF Vectorizer
- Text Preprocessing: Stemming + Stopword Removal

##  Output
Enter a news article in the Streamlit app, and the model predicts whether it is *Fake* or *Real*
