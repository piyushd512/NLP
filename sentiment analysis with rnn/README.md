### Sentiment Analysis Notebook with Various Language-Based Models

This notebook provides an analysis of sentiment classification using multiple language-based models. The following models are employed:

- **Logistic Regression**: Achieves an accuracy of 83.51% on the training data and 77.31% on the testing data.
- **Linear Support Vector Classifier (LinearSVC)**: Attains an accuracy of 93.10% on the training data and 76.34% on the testing data.
- **Random Forest Classifier**: Reports an accuracy of 75.49% on the training data and 70.90% on the testing data.
- **Bernoulli Naive Bayes**: Yields an accuracy of 86.85% on the training data and 75.79% on the testing data.
- **Long Short-Term Memory (LSTM)**: Demonstrates an accuracy of 82.85% on the training data and 76.31% on the testing data after 10 epochs.

#### Libraries Used:
- TensorFlow
- NumPy
- Pandas
- NLTK
- Scikit-learn
- Regular Expressions (re)
- WordCloud
- String

#### Analysis:
The notebook explores the performance of various machine learning and deep learning models for sentiment analysis. It provides insights into each model's accuracy on both training and testing datasets, helping to assess their effectiveness in classifying sentiment.

#### Usage:
1. **Data Preprocessing**: The notebook preprocesses the text data, including tasks such as tokenization, removal of stopwords, and vectorization.
2. **Model Training**: Each model is trained using the preprocessed data, and its performance metrics are evaluated.
3. **Evaluation and Comparison**: The accuracy of each model on the training and testing datasets is compared to determine their effectiveness in sentiment classification.


#### Contributions:
Contributions to the notebook, including enhancements, bug fixes, and additional models, are welcome. Feel free to suggest improvements or submit pull requests to enhance the sentiment analysis analysis.
