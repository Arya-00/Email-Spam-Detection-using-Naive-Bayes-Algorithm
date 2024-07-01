# Email Spam Detection using Naive Bayes Algorithm

This project demonstrates the implementation of an Email Spam Detection system using the Naive Bayes algorithm from scratch. The project includes handling the underflow problem using Log Naive Bayes.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Implementation](#implementation)
  - [Data Preprocessing](#data-preprocessing)
  - [Feature Extraction](#feature-extraction)
  - [Model Training](#model-training)
  - [Model Evaluation](#model-evaluation)
  - [Handling Underflow with Log Naive Bayes](#handling-underflow-with-log-naive-bayes)
- [Requirements](#requirements)
- [Results](#results)
- [Conclusion](#conclusion)
- [Contributing](#contributing)

## Introduction
This project aims to detect spam emails using the Naive Bayes algorithm implemented from scratch. Naive Bayes is a simple yet powerful probabilistic classifier based on applying Bayes' theorem with strong (naive) independence assumptions between the features.

## Dataset
The dataset used for this project consists of labeled emails, where each email is categorized as either "spam" or "not spam." The dataset can be sourced from given file.

## Implementation
### Data Preprocessing
1. **Loading the Data:** Load the dataset into the program.
2. **Cleaning the Data:** Remove unnecessary characters, punctuations, and stop words.
3. **Tokenization:** Split the emails into individual words (tokens).

### Feature Extraction
1. **Vectorization:** Convert the tokens into word dictionary.

### Model Training
1. **Training the Naive Bayes Classifier:** Implement the Naive Bayes algorithm from scratch.
2. **Calculating Probabilities:** Compute the prior probabilities of spam and not spam emails, and the likelihood of each word given the spam and not spam classes.

### Model Evaluation
1. **Testing the Model:** Evaluate the model's performance on a test dataset.
2. **Metrics:** Use metrics such as accuracy, precision, recall, and F1-score to assess the model's performance.

### Handling Underflow with Log Naive Bayes
1. **Log Transformation:** Implement Log Naive Bayes to handle underflow issues by using logarithms of the probabilities instead of the raw probabilities.
2. **Probability Summation:** Sum the logarithms of the probabilities rather than multiplying the raw probabilities.

## Requirements
1. Pandas V.2.2.1
2. Numpy V.1.26.4
3. NLTK V.3.8.1

## Results
1. Accuracy: `99.21%`
2. Recall: `98.03%`
3. Precision: `98.42%`

## Conclusion
This project demonstrates the effectiveness of the Naive Bayes algorithm for spam detection. By implementing the algorithm from scratch and addressing the underflow problem using Log Naive Bayes, we achieved a robust spam detection system.

## Contributing
Contributions are welcome! Please fork this repository and submit pull requests with detailed descriptions of the changes.
