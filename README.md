# Naive Bayes Email Classifier

This Colab notebook demonstrates a simple email spam classifier using the Naive Bayes algorithm. 

## Dataset

The notebook uses a CSV dataset containing labeled emails, classifying them as either spam or not spam (ham). You need to upload the dataset (spam_ham_dataset.csv) to Colab to run this notebook. 

## Workflow

1. **Load Data:** Reads the uploaded CSV file into a pandas DataFrame.
2. **Data Preprocessing:** Cleans the data by removing unnecessary columns.
3. **Split Data:** Divides the data into training and testing sets.
4. **Feature Extraction:**  Converts email text into a numerical representation (Bag-of-Words) using `CountVectorizer`.
5. **Model Training:** Trains a Multinomial Naive Bayes model on the training data.
6. **Model Evaluation:** 
    - Predicts the class of the test emails.
    - Calculates the accuracy and classification report.
    - Generates a confusion matrix to visualize the model's performance.
7. **Cross-Validation:**
    - Implements cross-validation to assess the model's robustness and to further evaluate its performance.
8. **New Email Prediction:**
    - Allows for input of a new email and predicts whether it is spam or ham using the trained model.


## How to use

1. Upload your 'spam_ham_dataset.csv' file to Colab by running the relevant cells.
2. Run the code step by step.


## Libraries Used

- pandas: Data manipulation.
- sklearn: Model building, training, and evaluation.
- seaborn, matplotlib: Visualization.
- io: Handling input/output streams.

## Note
 This is a basic implementation for demonstration purposes. You can modify and extend it further by adding more preprocessing steps, feature engineering techniques, or other algorithms for improved performance. 
