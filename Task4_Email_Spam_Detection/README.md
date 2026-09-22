# Task 4 - Email Spam Detection

## Objective

The objective of this project is to build a machine learning model that can classify SMS messages as either **Ham (legitimate)** or **Spam (unwanted)**.

## Dataset

The project uses the **SMS Spam Collection** dataset from the UCI Machine Learning Repository.

The dataset contains SMS messages labeled as:

- **Ham** - Normal/legitimate message
- **Spam** - Unwanted or promotional message

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Multinomial Naive Bayes

## Project Workflow

1. Load the SMS Spam Collection dataset
2. Explore the dataset
3. Check missing values
4. Remove duplicate records
5. Convert labels into numerical values
6. Split the dataset into training and testing data
7. Convert text into numerical features using TF-IDF
8. Train a Multinomial Naive Bayes model
9. Make predictions on test data
10. Evaluate the model using accuracy, precision, recall and F1-score
11. Analyze the confusion matrix
12. Test the model with custom SMS messages

## Machine Learning Model

### Multinomial Naive Bayes

Multinomial Naive Bayes is a classification algorithm commonly used for text classification problems.

It was trained using TF-IDF features extracted from the SMS messages.

## Evaluation Metrics

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Project File

- `YuvasreeM_Task4.ipynb` - Complete Jupyter Notebook containing data preprocessing, visualization, model training and evaluation.

## Conclusion

The Email Spam Detection project demonstrates how Natural Language Processing and Machine Learning can be used to automatically classify SMS messages as Ham or Spam.

The Multinomial Naive Bayes model combined with TF-IDF text features achieved good classification performance and successfully predicted custom unseen messages.