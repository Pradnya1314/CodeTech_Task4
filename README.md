## Machine Learning Model Implementation

This project is a simple spam message classifier built using Python and Scikit-learn. It uses a Naive Bayes algorithm to detect 
whether a given SMS message is **Spam** or **Ham (Not Spam)**.

## Features

- Classifies SMS messages as Spam or Ham
- Uses CountVectorizer for text preprocessing
- Implements Multinomial Naive Bayes for classification
- Outputs accuracy, confusion matrix, and classification report
- Includes a sample dataset (`spam.csv`) with labeled messages

## Technologies Used

- Python
- Pandas
- Scikit-learn

## Files

- spam_detector.py : Main Python script for training and testing the model
- spam.csv : Dataset with SMS messages labeled as `ham` or `spam`
- Spam Email detection : output screenshot
  
##  Installation

1. Clone this repository:
   
   git clone https://github.com/your-username/spam-detector.git
   cd spam-detector

2. Create a virtual environment:

python -m venv .venv
.venv\Scripts\activate   # On Windows
Install required packages:

pip install pandas scikit-learn

▶How to Run
Make sure spam.csv is in the same directory as spam_detector.py.

## Run the script:

python spam_detector.py

You’ll see the accuracy score, confusion matrix, and a classification report printed in the terminal.

## Submitted

Pradnya Pramod Mhatre
Intership:CodeTech_Task4

