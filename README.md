# NLP Spam Filter

## Overview
This Jupyter Notebook contains code for building a Natural Language Processing (NLP) spam filter using the Naive Bayes classifier. The dataset used for training and testing the model is sourced from a YouTube comments dataset (Youtube01-Psy.csv).

## Instructions
To run the notebook, follow these steps:

1. **Load the Data**: The notebook begins by loading the dataset into a Pandas DataFrame and displaying basic information about the data.

2. **Prepare the Data for Model Building using NLTK**: The data preprocessing step involves tokenization, vectorization using CountVectorizer, and downsizing the transformed data using TF-IDF.

3. **Shuffle and Split the Data**: The dataset is shuffled, and then split into training (75%) and testing (25%) sets. The comments and their corresponding spam labels are separated.

4. **Fit Naive Bayes Classifier and Cross-Validate**: The notebook fits the training data into a Naive Bayes classifier and performs cross-validation to evaluate the model's accuracy.

5. **Test the Model on the Test Set and Check Accuracy**: The trained model is tested on the test data, and the confusion matrix along with the accuracy is displayed.

6. **Pass New Comments to Classifier and Check for Spam**: New comments are created, passed through the trained classifier, and predictions for spam or non-spam are shown.

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries: pandas, sklearn

## Acknowledgments
- Dataset source: YouTube Spam Collection [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/380/youtube+spam+collection)
- COMP 237 course term project.
