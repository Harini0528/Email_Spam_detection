This project implements a Spam Detection System using Machine Learning, specifically Logistic Regression, to classify messages as either spam or ham (not spam). It utilizes TF-IDF vectorization for feature extraction and evaluates performance using various metrics.

Dataset: Uses a CSV file (spam.csv) containing labeled messages.

Preprocessing:
Converts spam/ham labels into binary values (0 for spam, 1 for ham).
Splits data into training and testing sets.
Extracts text features using TF-IDF Vectorization.
Model Training: Trains a Logistic Regression model on the extracted features.

Evaluation:
Computes accuracy, precision, recall, specificity.
Generates a confusion matrix and classification report.

Prediction:
Allows user input for live spam detection.

Dependencies:
The script requires the following Python libraries:
numpy
pandas
matplotlib
seaborn
sklearn

Usage:
Ensure the dataset (spam.csv) is present in the same directory.
Run the script in a Python environment.
Enter a message when prompted to classify it as spam or ham.

Output:
Model accuracy on training and test sets.
Confusion matrix visualization.
Classification metrics (precision, recall, specificity).
Real-time spam detection for user input.
