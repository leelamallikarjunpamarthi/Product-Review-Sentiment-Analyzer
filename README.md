# Product-Review-Sentiment-Analyzer
This project is a machine learning model that performs sentiment analysis on a dataset of product reviews. The goal is to classify reviews as either positive, negative, or neutral based on the text content.

# Features
**Data Preprocessing**: Loads and samples a CSV dataset.

**Vectorization**: Converts text reviews into numerical feature vectors using CountVectorizer.

**Model Training**: Trains two classification models:

**Multinomial Naive Bayes**: A text classifier that uses word counts to predict a class, like sentiment.

**Random Forest Classifier**: An algorithm that combines multiple decision trees to improve prediction accuracy.

**Model Evaluation**: Calculates and prints the accuracy score and a detailed classification report for each model.

**Data Visualization**: Generates a word cloud to visualize the most frequent words in the reviews.

# Technologies Used
**Python** :Main programming language used.

**Pandas**: For data manipulation and analysis.

**Scikit-learn**: For machine learning model implementation, including CountVectorizer, MultinomialNB, RandomForestClassifier, train_test_split, and accuracy_score.

**Matplotlib**: For plotting and visualizations.

**WordCloud**: For generating word cloud visualizations.
