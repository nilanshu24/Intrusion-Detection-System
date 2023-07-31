# Intrusion Detection System

This repository contains code for an Intrusion Detection System (IDS) implemented using machine learning techniques. The IDS is designed to detect and classify different types of network attacks.

## Description

The IDS code implements the NSL-KDD dataset, which is a popular dataset used for evaluating intrusion detection systems. The train and test files from the NSL-KDD dataset are used to process the data and map the attacks.

The code utilizes the `RandomForestClassifier` from the `sklearn` library to train the IDS model. The RandomForestClassifier is used for feature selection, and a graphical representation is formed to visualize the importance of each feature. This feature selection step helps in identifying the most relevant features for the intrusion detection system.

The code also includes data preprocessing steps, such as one-hot encoding of categorical features and finalizing the data for training the IDS. The preprocessed data is then used to train the IDS model and obtain accuracy scores.

## Dataset

The NSL-KDD dataset is used for training and testing the IDS. It consists of labeled instances for various types of network attacks. The dataset is divided into train and test files, which are used for model training and evaluation.

Please ensure that you have the NSL-KDD dataset files (`train` and `test`) available in the same directory as the code files before running the code.

## Dependencies

The code is written in Python and relies on the following libraries:

- scikit-learn: For machine learning algorithms and evaluation metrics.
- pandas: For data manipulation and preprocessing.
- numpy: For numerical operations.
- matplotlib: For data visualization.
- other standard Python libraries

Ensure that you have these libraries installed before running the code.

## Usage

To use this code:

1. Clone the repository: `git clone https://github.com/nilanshu24/intrusion-detection-system.git`
2. Place the NSL-KDD dataset files (`train` and `test`) in the same directory as the code files.
3. Install the required dependencies: `pip install scikit-learn pandas numpy matplotlib`
4. Adjust the code to your specific requirements, such as modifying the feature selection parameters or hyperparameters of the RandomForestClassifier.
5. Run the main script: `python main.py`
6. The script will preprocess the data, perform feature selection, train the IDS model using RandomForestClassifier, and output the accuracy of the model.

Feel free to experiment with different feature selection methods, classifiers, or hyperparameters to improve the performance of the intrusion detection system.

## Contribution

Contributions to this project are welcome. If you have any suggestions, bug fixes, or feature enhancements, please submit a pull request or open an issue.
