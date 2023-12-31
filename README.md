# Credit Card Fraud Detection system

Detect and prevent credit card fraud in real-time using advanced machine learning techniques.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Dataset](#dataset-source-and-description)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

Welcome to the  Credit Card Fraud Detector project!

In today's digital age, credit card fraud has become an increasingly prevalent threat, costing both individuals and businesses billions of dollars annually. The goal of our project is to tackle this issue by developing an advanced credit card fraud detection system that operates proactively, identifying potential fraud patterns before they escalate into significant financial losses.


**Key Features**
- **Proactive Detection**: Unlike traditional fraud detection systems that often flag transactions after the fact, our solution aims to identify suspicious activities in real-time, enabling swift intervention and prevention.

- **Machine Learning and AI Power**: Leveraging the capabilities of machine learning algorithms, we're able to analyze complex patterns and anomalies within large-scale transaction datasets, improving the accuracy of our fraud detection.

- **User-Friendly Interface**: Our user interface provides an intuitive dashboard that allows users to monitor transactions, view alerts, and access comprehensive reports, making it easy to manage and respond to potential threats.


**Objectives**
- **Enhanced Security**: By identifying and stopping fraudulent activities in their early stages, we aim to provide enhanced security for both individuals and businesses, reducing financial losses and increasing trust in financial systems.

- **Educational Resource**: This project also serves as an educational resource for aspiring data scientists and machine learning enthusiasts. The accompanying documentation and codebase offer insights into implementing real-world fraud detection solutions.

- **Community Collaboration**: We encourage collaboration from the open-source community to improve the effectiveness of our fraud detection model. We believe that by working together, we can stay one step ahead of evolving fraud tactics.

Whether you're an individual concerned about the safety of your financial transactions or a developer interested in learning about machine learning and fraud detection, our Proactive Credit Card Fraud Detector project aims to provide valuable insights and tools to address the challenges posed by credit card fraud.



## Installation

Getting started with the  Credit Card Fraud Detector is straightforward. Follow these steps to set up the project on your local machine.

### Prerequisites

- Python 3.6 or higher
- Pip (Python package manager)
example : `pip install numpy`

### Clone the Repository

command line : 

- git clone https://github.com/mohibr1993/Credit_Card_Fraud_Detection.git

- cd Credit_Card_Fraud_Detection

### Install Dependencies



Install the required Python packages:


pip install -r requirements.txt
The project relies on various external libraries for its functionality. Here are some of the key libraries you'll be using:

- numpy: A library for numerical operations and linear algebra.
- pandas: A library for data processing and analysis, including CSV file I/O.
- tensorflow: A machine learning framework for building and training models.
- matplotlib: A plotting library for creating visualizations.
- seaborn: A data visualization library based on Matplotlib, providing additional aesthetics.
- sklearn: The scikit-learn library provides various machine learning algorithms and tools.
- imblearn: A library for handling imbalanced datasets, including resampling techniques.

## Dataset-source-and-description
**Data Source**
Link : [https://www.kaggle.com/uciml/defaultof-credit-cardclients-dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.

Update (03/05/2021)
A simulator for transaction data has been released as part of the practical handbook on Machine Learning for Credit Card Fraud Detection - https://fraud-detection-handbook.github.io/fraud-detection-handbook/Chapter_3_GettingStarted/SimulatedDataset.html. We invite all practitioners interested in fraud detection datasets to also check out this data simulator, and the methodologies for credit card fraud detection presented in the book.


The Credit Card Fraud Detection dataset has 28 features, below description is expectation for what the data , it's just to simplify understant of data and credit card field , it's may true or false :

- Time: The time of the transaction in seconds since the first transaction in the dataset.
- Amount: The amount of the transaction in euros.
- Class: The class of the transaction, which is 1 for fraud and 0 for non-fraud.
- V1: The difference in the amount of the current transaction and the previous transaction.
- V2: The difference in the amount of the current transaction and the mean amount of the previous 28 transactions.
- V3: The difference in the amount of the current transaction and the median amount of the previous 28 transactions.
- V4: The ratio of the amount of the current transaction to the mean amount of the previous 28 transactions.
- V5: The ratio of the amount of the current transaction to the median amount of the previous 28 transactions.
- V6: The standard deviation of the amount of the previous 28 transactions.
- V7: The skewness of the amount of the previous 28 transactions.
- V8: The kurtosis of the amount of the previous 28 transactions.
- V9: The number of times the same merchant has been used in the previous 28 transactions.
- V10: The number of times the same product has been purchased in the previous 28 transactions.
- V11: The number of days since the customer's last transaction.
- V12: The customer's age.
- V13: The customer's gender.
- V14: The customer's city.
- V15: The customer's state.
- V16: The customer's country.
- V17: The merchant's city.
- V18: The merchant's state.
- V19: The merchant's country.
- V20: The type of card used.
- V21: The day of the week the transaction occurred.
- V22: The hour of the day the transaction occurred.
- V23: The weekend flag (1 if the transaction occurred on a weekend, 0 otherwise).
- V24: The month the transaction occurred.
- V25: The year the transaction occurred.
- V26: The latitude of the customer's location.
- V27: The longitude of the customer's location.
- V28: The device type used for the transaction.

The features V1 to V28 are **numerical features**. The feature Class is a **categorical feature**.

## Contributing

We welcome contributions to the  Credit Card Fraud Detector project from the community. If you're interested in contributing, please follow these guidelines:

- **Issues**: If you encounter any issues or have suggestions, feel free to open an issue on our [Report Problems and Suggest Features](https://github.com/mohibr1993/Credit_Card_Fraud_Detection.git/issues). Please provide a clear description of the problem or suggestion.

- **Feature Requests**: If you have an idea for a new feature, you can also open an issue to discuss it. We value your input and would love to hear about your ideas.

- **Pull Requests**: If you want to contribute code, you can fork the repository, make your changes, and submit a pull request. Please ensure your code follows our coding standards and practices.


## License

This project is licensed under the [MIT License](LICENSE.md). By contributing to this project, you agree to abide by the terms of this license.

## Contact

If you have any questions, suggestions, or feedback, feel free to reach out to us. You can contact the project maintainers through the following channels:

- Project Maintainer: [mohibr1993](mailto:m.e.mohibr@gmail.com)
- GitHub Issues:  [Report Problems and Suggest Features](https://github.com/mohibr1993/Credit_Card_Fraud_Detection.git/issues)

We appreciate your interest in the Credit Card Fraud Detector project and look forward to hearing from you!





