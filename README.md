# README

## Overview

This repository contains an AI model for classifying emails as either spam or ham. The model uses a Naive Bayes classifier, SVM, and Random Forest classifiers to predict whether an email is spam or not. The dataset used for training and testing the model is a CSV file named 'emails.csv'.

## Prerequisites

Before running the code, ensure that you have the following libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- sklearn

You can install them using pip:

```bash
pip install pandas numpy matplotlib seaborn sklearn
```

## Usage

To use the model, follow these steps:

1. Clone this repository.
2. Run the Python script.

## Model Details

The model is trained and tested using three different classifiers: Naive Bayes, SVM, and Random Forest. The Naive Bayes classifier is trained first, followed by the SVM and Random Forest classifiers. The model's performance is evaluated using a confusion matrix and a classification report.

## Dataset

The dataset used for training and testing the model is a CSV file named 'emails.csv'. The dataset contains two columns: 'text' and 'spam'. The 'text' column contains the email text, and the 'spam' column indicates whether the email is spam (1) or not (0).

## Code Explanation

The code is divided into several steps:

1. **Importing Libraries**: The necessary Python libraries are imported.
2. **Importing Dataset**: The 'emails.csv' dataset is loaded into a pandas DataFrame.
3. **Visualising Dataset**: The dataset is visualized using seaborn and matplotlib.
4. **CountVectorizer**: The 'text' column of the dataset is vectorized using CountVectorizer from sklearn.
5. **Training the Model**: The Naive Bayes classifier is trained using the vectorized 'text' column and the 'spam' column.
6. **Evaluating the Model**: The model's performance is evaluated using a confusion matrix and a classification report.

## Contributing

Contributions are welcome. Please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

This project uses the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- sklearn

[Source 1](https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/)
[Source 3](https://pypi.org/project/readmeai/)
