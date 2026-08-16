# Fake News Detection Using Machine Learning

## Project Overview

This project detects whether a news article is **Fake or Real** using Natural Language Processing (NLP) and Machine Learning.

## Objective

The objective of this project is to build a machine learning model that classifies news articles as Fake or Real based on their textual content.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- TF-IDF
- Logistic Regression

## Methodology

The project follows these steps:

1. Dataset Loading
2. Data Cleaning and Preprocessing
3. Train-Test Split
4. TF-IDF Feature Extraction
5. Logistic Regression Model Training
6. Model Evaluation
7. Fake/Real News Prediction

## Machine Learning Model

**Logistic Regression** was used as the classification algorithm.

TF-IDF (Term Frequency-Inverse Document Frequency) was used to convert the news text into numerical features suitable for machine learning.

## Results

The model achieved:

- **Accuracy: 98.86%**
- **AUC Score: 1.00**

The model demonstrated strong performance in distinguishing between Fake and Real news articles on the test dataset.

## Project Files

| File | Description |
|---|---|
| `Fake_News_Detection_Project.ipynb` | Complete project notebook |
| `fake_news_model.pkl` | Trained Logistic Regression model |
| `tfidf_vectorizer.pkl` | Trained TF-IDF vectorizer |
| `requirements.txt` | Required Python libraries |
| `Fake_News_Detection_Report.pdf` | Project report |
| `Classification_Report.png` | Classification report result |
| `Confusion_Matrix.png` | Confusion matrix visualization |
| `ROC-curve.png` | ROC curve visualization |
| `Training TF-IDF shape.png` | TF-IDF training feature information |
| `train_test_split.png` | Train-test split information |

## How to Run

1. Open `Fake_News_Detection_Project.ipynb` using Google Colab or Jupyter Notebook.
2. Install the required libraries from `requirements.txt`.
3. Load the required dataset.
4. Run the notebook cells in order.
5. Enter a news article when prompted to obtain a Fake or Real prediction.

## Project Screenshots

The repository contains screenshots showing:

- Train-Test Split
- TF-IDF Feature Extraction
- Classification Report
- Confusion Matrix
- ROC Curve

## Future Scope

The project can be improved by:

- Using larger and more diverse datasets
- Applying advanced NLP techniques
- Experimenting with other machine learning algorithms
- Using deep learning and transformer-based models
- Developing a web-based interface for real-time prediction

## Conclusion

This project demonstrates the application of Natural Language Processing and Machine Learning for automated fake news detection.

The combination of **TF-IDF and Logistic Regression** provides an effective and efficient approach for classifying news articles as Fake or Real.
