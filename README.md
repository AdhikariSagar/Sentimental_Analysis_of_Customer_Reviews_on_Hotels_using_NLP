# Sentiment Analysis of Customer Reviews using NLP

### Introduction

Sentiment analysis is crucial for businesses to understand customer feedback, gauge satisfaction levels, and identify areas for improvement. This project focuses on analyzing hotel reviews across Europe using Natural Language Processing (NLP) techniques and various machine learning models. The goal is to predict the sentiment of new comments and classify them as positive or negative.

### Data Preparation

The dataset includes hotel reviews with information such as hotel addresses, reviewer nationalities, review sentiments (positive or negative), and review scores. For sentiment analysis, we focus on the text data and classify reviews based on their ratings: scores below 5 are considered 'bad', while scores above 5 are 'good'. Placeholder comments like "No Negative" or "No Positive" are removed during preprocessing.
Text Preprocessing

Text preprocessing steps include tokenization, stop word removal, and lemmatization to clean and prepare the textual data for analysis.
Model Building

Several classical machine learning classifiers were evaluated for sentiment analysis:

    BernoulliNB
    RandomForest
    SVC
    Logistic Regression
    DecisionTree
    KNeighbors

Based on accuracy comparisons, Logistic Regression performed the best with an accuracy of 94.8%. SVC and RandomForestClassifier also achieved high accuracies of 94.5% and 94.3%, respectively.

### Sentiment Analysis with Deep Learning using BERT

In addition to traditional machine learning models, a sentiment analysis model was developed using pre-trained BERT (Bidirectional Encoder Representations from Transformers) for deep learning. This model leverages PyTorch for implementation and achieves competitive accuracy after fine-tuning.
### Conclusion

This repository provides tools and models for sentiment analysis of hotel reviews, offering insights into customer satisfaction and enhancing decision-making processes for businesses in the hospitality industry.

For detailed implementation and results, please refer to our code and documentation in this repository.

Feel free to adjust the sections or add more details based on your specific project's findings and requirements!
