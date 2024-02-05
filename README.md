# classification-challenge
# Spam Email Detector

## Project Overview
This Spam Email Detector is a machine learning project aimed at classifying emails as either spam or non-spam. The project uses two different models: Logistic Regression and Random Forest Classifier, to predict whether an email is spam. The dataset used for this project is sourced from the [UCI Machine Learning Library](https://archive.ics.uci.edu/dataset/94/spambase).

## Features
- **Data Preprocessing:** Includes scaling and splitting the dataset into training and testing sets.
- **Model Training and Evaluation:** Implements two different machine learning models.
- **Model Comparison:** Compares the performance of Logistic Regression and Random Forest Classifier models.
- **Accuracy Assessment:** Evaluates the models based on their accuracy in classifying emails.

## Installation
To run this project, you need to have Python installed on your system. The project also requires the following Python libraries:
- Pandas
- scikit-learn

You can install these packages using pip:
```bash
pip install pandas scikit-learn
```

## Usage
To use this project, clone the repo and run the main script. Make sure to have the dataset `spam-data.csv` in the same directory as the script.

```bash
git clone <repo-url>
cd <repo-directory>
python spam_detector.py
```

## Dataset
The dataset used in this project can be found at [https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv](https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv). It is a collection of various features based on the frequency of words and characters in emails, alongside some statistical features derived from email content.

## Models
1. **Logistic Regression:** A basic model for binary classification tasks.
2. **Random Forest Classifier:** An ensemble model that is more complex and tends to capture non-linear relationships better.

## Results
The models were evaluated based on their accuracy in classifying emails as spam or non-spam. In our tests, the Random Forest Classifier showed a higher accuracy compared to the Logistic Regression model.

## Contributing
Contributions to this project are welcome. Please ensure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
