# CreditCard
Project involves detecting credit card fraud using Logistic Regression and Random Forest classifiers. models are trained and evaluated. The script provides a comparison of performance metrics, including confusion matrices and classification reports, for both algorithms. 
Here's a README file for your project:

---

# Credit Card Fraud Detection

This project involves detecting fraudulent credit card transactions using two machine learning algorithms: Logistic Regression and Random Forest. The dataset used is `creditcard.csv`, which contains transaction details and labels indicating whether the transaction is fraudulent.

## Project Overview

The project performs the following steps:
1. **Data Preprocessing**: Normalize the features (excluding 'Time' and 'Class').
2. **Model Training and Evaluation**:
   - Logistic Regression
   - Random Forest Classifier

## Files

- `creditcard.csv`: The dataset containing transaction details.
- `fraud_detection.py`: Python script containing code for data preprocessing, model training, and evaluation.

## Dependencies

The project requires the following Python libraries:
- `pandas`
- `scikit-learn`

You can install these dependencies using pip:
```bash
pip install pandas scikit-learn
```

## Code Explanation

1. **Loading Data**: 
   - The dataset is loaded into a pandas DataFrame.

2. **Data Normalization**: 
   - Features (excluding 'Time' and 'Class') are normalized using `MinMaxScaler`.

3. **Logistic Regression**:
   - The data is split into training and test sets.
   - A Logistic Regression model is trained and evaluated.
   - Confusion matrix and classification report are printed.

4. **Random Forest Classifier**:
   - The data is split into training and test sets.
   - A Random Forest model is trained and evaluated.
   - Confusion matrix and classification report are printed.

## How to Run

1. Ensure you have the required dependencies installed.
2. Place the `creditcard.csv` file in the same directory as `fraud_detection.py`.
3. Run the script:
   ```bash
   python fraud_detection.py
   ```

## Results

The script outputs the confusion matrix and classification report for both models. This provides insights into the performance of each model in terms of accuracy, precision, recall, and F1-score.

## Notes

- The dataset should be preprocessed to handle missing values if any.
- Adjust hyperparameters as needed for improved performance.

---

Feel free to modify any sections to better fit your project specifics!
