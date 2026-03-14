# AI-Based Phishing Website Detection System

This project builds a machine learning model to detect phishing websites using URL-based features.

## Model
Random Forest Classifier

## Accuracy
89%

## Features Used
1. url_length
2. n_dots
3. n_hyphens
4. n_underline
5. n_slash
6. n_questionmark
7. n_equal
8. n_at
9. n_and
10. n_exclamation
11. n_space
12. n_tilde
13. n_comma
14. n_plus
15. n_asterisk
16. n_hashtag
17. n_dollar
18. n_percent
19. n_redirection
20. phishing (target label)


## Dataset
Dataset used for training can be downloaded from:

https://www.kaggle.com/datasets/shashwatwork/web-page-phishing-detection-dataset

## Workflow
1. Data preprocessing
2. Train-test split
3. Random Forest model training
4. Model evaluation
5. Feature importance analysis
6. Model saved using Pickle

## Technologies
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Google Colab
