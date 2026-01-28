# MACHINE-LEARNING-MODEL-IMPLEMENTATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SNEHA KAGAWADE

*INTERN ID*: CTIS2007

*DOMAIN*: PYTHON PROGRAMMING

*DURATION*: 4 WEEKS

Description

This project focuses on implementing a machine learning model using Python to classify messages as Spam or Not Spam. The model is built using the Scikit-learn library and applies Natural Language Processing (NLP) techniques to process and analyze text data. A publicly available SMS dataset is used to train and evaluate the model.

Objective

The primary objectives of this task are:

To build a predictive machine learning model using Scikit-learn

To preprocess and convert text data into numerical features

To classify SMS messages as spam or non-spam

To evaluate the model using standard performance metrics

Dataset Used

The dataset is sourced from a public GitHub repository and contains SMS messages labeled as:

Ham (0) – Legitimate messages

Spam (1) – Unwanted promotional or fraudulent messages

Each record consists of a message label and the corresponding text message.

Tools & Libraries Used

Python

Pandas & NumPy – data handling and preprocessing

Scikit-learn – machine learning model building and evaluation

Matplotlib & Seaborn – data visualization

Methodology

The dataset is first loaded and explored using Pandas. The text labels are converted into numerical values for model compatibility. The dataset is then split into training and testing sets using an 80:20 ratio.

Text data is transformed into numerical feature vectors using TF-IDF (Term Frequency–Inverse Document Frequency) Vectorization, which helps capture the importance of words while reducing the impact of common terms.

A Multinomial Naive Bayes classifier is trained on the vectorized training data. This algorithm is well-suited for text classification problems due to its efficiency and probabilistic approach.

Model Evaluation

The trained model is evaluated using:

Accuracy Score

Classification Report (Precision, Recall, F1-score)

Confusion Matrix (visualized using a heatmap)

These metrics provide insight into how well the model distinguishes between spam and non-spam messages.

Prediction Functionality

A custom function is implemented to predict whether a new, unseen message is spam or not. This allows real-time testing of the model using user-defined input messages.

Results

The model achieves high accuracy in classifying SMS messages.

The confusion matrix clearly shows correct and incorrect classifications.

The prediction function successfully identifies spam messages based on learned patterns.

Conclusion

This project successfully demonstrates the implementation of a machine learning classification model using Scikit-learn. It fulfills the requirements of CODTECH Internship – Task 4 by applying NLP techniques, building a predictive model, and evaluating its performance. The project provides practical exposure to real-world machine learning workflows and text classification tasks.

Learning Outcomes

Understanding text preprocessing and vectorization

Building classification models using Scikit-learn

Evaluating machine learning models using standard metrics

Applying NLP techniques for real-world problems

<img width="343" height="174" alt="Image" src="https://github.com/user-attachments/assets/1c9325d2-0971-4fd4-bf67-8992572db3e2" />

<img width="434" height="322" alt="Image" src="https://github.com/user-attachments/assets/5a3859d9-ca33-421b-91b9-3bdfe789a4cb" />
