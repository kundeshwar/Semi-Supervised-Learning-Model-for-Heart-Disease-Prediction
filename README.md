# Semi-Supervised-Learning-Model-for-Heart-Disease-Prediction
This project aims to predict the presence or absence of heart disease using a semi-supervised learning approach.
This project aims to predict the presence or absence of heart disease using a semi-supervised learning approach. The dataset used for this project is the Heart Disease UCI dataset from the UCI Machine Learning Repository. This dataset contains 303 instances and 14 attributes including age, sex, chest pain type, and cholesterol level.

- Requirements
- Python 3.6+
- Pandas
- Scikit-learn
- mlxtend
- Installation
- You can install the required libraries using pip:

**Copy code** <br>
pip install pandas scikit-learn mlxtend <br>
**Usage**
1. Clone the repository and navigate to the project directory.
2. Download the dataset and place it in the project directory. <br>
<br>
Run the heart_disease_prediction.py file using Python.<br>
The heart_disease_prediction.py file contains the code for the semi-supervised learning model. The dataset is loaded into a Pandas DataFrame and preprocessed to handle missing values. The data is then split into training, test, and unlabeled datasets.

A logistic regression model is trained on the labeled training data. The accuracy of the model is evaluated using the training data and a classification report and confusion matrix are generated. The trained model is then used to predict the labels for the unlabeled data.

The labeled training data and predicted labels for the unlabeled data are combined to create a new training set. A logistic regression model is then trained on the new training set.

The trained model is used to predict the presence or absence of heart disease for new data. An example input is provided in the code, which can be modified to test the model on different inputs.

**Results**  <br>
The semi-supervised learning model achieved an accuracy of 80% on the test data. The confusion matrix and classification report are generated to evaluate the performance of the model.

**Conclusion** <br>
Semi-supervised learning is a useful technique for making predictions when labeled data is limited. This project demonstrates the effectiveness of a semi-supervised learning model for predicting the presence or absence of heart disease.
