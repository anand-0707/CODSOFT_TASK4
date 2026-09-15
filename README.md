# SMS Spam Detection Using TF-IDF and Machine Learning

## 📌 Project Overview

This project focuses on detecting whether an SMS message is **Spam** or **Ham (Not Spam)** using Machine Learning and Natural Language Processing techniques.

The project uses **TF-IDF (Term Frequency-Inverse Document Frequency)** to convert SMS text into numerical features and then applies a Machine Learning classification algorithm.

## 🎯 Objective

The main objective of this project is to automatically classify SMS messages as spam or legitimate messages.

## 📂 Dataset

The dataset contains **5,572 SMS messages** with two main columns:

* `v1` – Message category (`ham` or `spam`)
* `v2` – SMS message text

The unnecessary columns were removed during data preprocessing.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* TF-IDF
* Matplotlib
* Seaborn
* Jupyter Notebook

## 🔄 Project Workflow

1. Load the SMS dataset
2. Explore the dataset
3. Remove unnecessary columns
4. Prepare the message labels and text
5. Convert SMS text into numerical features using TF-IDF
6. Split the data into training and testing sets
7. Train a Machine Learning classification model
8. Evaluate the model performance
9. Predict whether new SMS messages are Spam or Ham

## 🤖 Machine Learning

TF-IDF is used for text feature extraction. The extracted features are then given to a Machine Learning classification model to classify SMS messages.

## 📊 Result

The trained model can classify SMS messages into two categories:

* **Ham** – Normal/legitimate message
* **Spam** – Unwanted or fraudulent message

## 💡 Conclusion

This project demonstrates how Natural Language Processing and Machine Learning can be combined to build an SMS spam detection system.

The system can automatically identify potentially unwanted spam messages and distinguish them from normal messages.
