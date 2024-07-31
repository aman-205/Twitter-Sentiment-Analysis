# Twitter-Sentiment-Analysis
This project aims to perform sentiment analysis on Twitter data using a logistic regression model. The sentiment analysis involves classifying tweets into positive, negative, or neutral sentiments. We leverage the Natural Language Toolkit (NLTK) for text preprocessing and feature extraction, and scikit-learn for building and evaluating the logistic regression model.

## Dataset
The dataset is expected to be a CSV file with at least the following columns:

text: The text of the tweet.
sentiment: The sentiment label (e.g., positive, negative, neutral).
Place your dataset in the data/ directory with the name dataset.csv.

### Data Preprocessing
Data preprocessing steps include:

Tokenization: Splitting text into individual words.
Stopword Removal: Removing common words that do not contribute to sentiment.
Stemming/Lemmatization: Reducing words to their base forms.
Vectorization: Converting text into numerical features using techniques such as TF-IDF.
Refer to notebooks/data_preprocessing.ipynb or src/preprocessing.py for details on these steps.

### Model Training
The logistic regression model is trained using features extracted from the preprocessed text data. We use scikit-learn's LogisticRegression for model training.
