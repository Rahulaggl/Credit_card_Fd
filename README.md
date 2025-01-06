

# Credit Card Fraud Detection

This project utilizes machine learning algorithms to identify unauthorized credit card transactions and prevent fraud. The solution involves data collection, preprocessing, and the use of predictive models like **Logistic Regression** and **Random Forests**. Techniques such as **rule-based systems**, **anomaly detection**, and **real-time monitoring** are incorporated to enhance fraud detection accuracy.

## Overview

Credit card fraud detection is an essential part of the financial industry, aiming to identify and prevent unauthorized transactions. By leveraging machine learning algorithms, this project creates a predictive model that can classify credit card transactions as either legitimate or fraudulent.

The dataset used for this project is sourced from **Kaggle** and contains details about credit card transactions, including features like transaction amount, user demographics, and transaction timestamps.

## Dataset

The dataset used for this project is available on **Kaggle**:

[Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

[Google Colab Link](https://colab.research.google.com/github/Rahulaggl/Credit_card_Fd/blob/main/CCD.ipynb#scrollTo=w3vuiKq6rqx1)

It contains features such as:

- **Transaction Amount**: The monetary value of the transaction.
- **Transaction Time**: The timestamp of the transaction.
- **User Information**: Demographic information about the cardholder.
- **Transaction Details**: Additional information about the transaction type and location.

You can also run the project on **Google Colab** for easy access and execution. Simply upload the dataset to Colab and follow the instructions below.

## Features

- **Data Preprocessing**: Cleaning, feature engineering, and handling imbalanced data.
- **Modeling**: Implementation of **Logistic Regression** and **Random Forest** classifiers.
- **Fraud Detection Techniques**:
  - **Rule-based Systems** for filtering known fraudulent activities.
  - **Anomaly Detection** to identify deviations from normal transaction patterns.
  - **Real-time Monitoring** for live transaction assessment.
- **Evaluation**: Metrics like **accuracy**, **precision**, **recall**, and **F1-score** to assess model performance.

## Installation

### Prerequisites

- Python 3.x
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `imbalanced-learn`

### Clone the Repository

```bash
git clone https://github.com/yourusername/credit-card-fraud-detection.git
```

### Install Dependencies

```bash
cd credit-card-fraud-detection
pip install -r requirements.txt
```

## Usage

1. **Data Preprocessing**:  
   Clean the dataset, handle missing values, and perform feature engineering.

2. **Model Training**:  
   Train the **Logistic Regression** and **Random Forest** models using the training data.

3. **Evaluation**:  
   Evaluate the models using accuracy, precision, recall, and F1-score. Tune hyperparameters to improve performance.

4. **Fraud Detection**:  
   Use the trained models to classify new credit card transactions as fraudulent or legitimate.


## Running on Google Colab

You can easily run the code on **Google Colab**. Just upload the dataset from Kaggle or from your local machine to Colab, and follow the steps outlined in the **Usage** section.

## Contributing

1. Fork this repository.
2. Create a feature branch.
3. Commit your changes.
4. Push your branch.
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

