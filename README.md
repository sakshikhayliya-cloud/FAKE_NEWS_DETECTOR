# Fake News Detector 📰

## About
A Machine Learning based system to detect 
fake news articles using NLP and TF-IDF.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- SQLite
- Tkinter GUI
- Jupyter Notebook

## Dataset
- Fake.csv (23,481 fake news articles)
- True.csv (21,417 real news articles)
- Total: 44,898 news articles

## Features
- Detects Fake or Real news
- GUI to enter and check news
- Results saved in SQL database
- 96.75% accuracy

## How to Run
1. Install requirements:
   pip install pandas scikit-learn numpy jupyter matplotlib seaborn
2. Open fake_news.ipynb
3. Run all cells
4. GUI will open automatically

## Results
- Accuracy: 98.57%
- Dataset: US English News (2017-2018)

## Limitations
- Trained on US news dataset
- Works best with English news
- Indian/Hindi news not supported
