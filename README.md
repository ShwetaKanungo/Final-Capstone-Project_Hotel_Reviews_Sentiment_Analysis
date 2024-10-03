# Final-Capstone-Project_Hotel_Reviews_Sentiment_Analysis
Sentiment analysis and topic modeling on hotel reviews using NLP. Classifies reviews into positive/negative sentiments and identifies key themes using machine learning models (Logistic Regression, Naive Bayes, SVM) and topic modeling techniques (LDA, NMF). Python libraries used for data processing and analysis.
# Hotel Reviews Sentiment Analysis and Topic Modeling

## Project Overview

This project focuses on analyzing hotel customer reviews to classify their sentiments (positive or negative) and extract common themes using topic modeling techniques like LDA and NMF. The aim is to help hotel businesses understand customer feedback to improve services and customer satisfaction.

## Dataset

The dataset contains reviews collected from various hotels, including metadata such as review dates, scores, reviewer nationality, and positive/negative review text. You can access a similar dataset [here](https://www.kaggle.com/code/jonathanoheix/sentiment-analysis-with-hotel-reviews/notebook#Conclusion).

## Key Deliverables

- **Data Preprocessing:** Text cleaning, tokenization, stopword removal, and lemmatization.
- **Exploratory Data Analysis (EDA):** Distribution of reviewer scores, sentiment trends, and word clouds for positive and negative reviews.
- **Sentiment Analysis Models:** Logistic Regression, Naive Bayes, and SVM for sentiment classification.
- **Topic Modeling:** Identifying common topics/themes in reviews using Latent Dirichlet Allocation (LDA) and Non-Negative Matrix Factorization (NMF).
- **Evaluation:** Accuracy, precision, recall, F1 score, and cross-validation.

## Project Structure

- **`Hotel_Reviews_Sentiment_Analysis.ipynb`**: The main Jupyter Notebook containing the code for data preprocessing, sentiment analysis, and topic modeling.
- **`data/`**: (Optional) A folder containing a sample dataset, if needed.
- **`code/`**: Additional Python scripts or code snippets used in the project (if applicable).
- **`Final_Report.pdf`**: The final project report that provides a detailed explanation of the project steps, results, and conclusions.
- **`requirements.txt`**: A file listing all the Python libraries and dependencies required to run the project.
  
## Dependencies

To run this project, you need to have the following Python libraries installed:

```bash
pandas==1.3.0
scikit-learn==0.24.2
nltk==3.6.2
matplotlib==3.4.2
WordCloud==1.8.1
Gensim==4.0.1
