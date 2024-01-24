# SMS Spam Detection with Machine Learning

### Ada Lovelace Academy | Data Science Academy - Project
-----

## Overview

This repository contains the source code and resources for building a machine learning model to classify SMS messages as either spam or not spam (ham). The model is trained on a dataset of labeled SMS messages using natural language processing (NLP) techniques to make predictions.

## Table of Contents

- [Installation](#installation)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Evaluation and Results](#evaluation-and-results)
- [License](#license)

## Installation

To run the code in this repository, you'll need to set up a environment with the necessary dependencies. You can install the required packages by running:

```bash
pip install -r requirements.txt
```
## Dataset

The dataset used for training and testing the SMS spam detection model is crucial for its performance. In this project, we utilized the [SMS Spam Collection dataset](https://www.kaggle.com/uciml/sms-spam-collection-dataset) from Kaggle, which contains a collection of SMS messages labeled as 'spam' or 'ham' (not spam).

### Dataset Source

- **Dataset Name:** SMS Spam Collection
- **Dataset Source:** [Kaggle - SMS Spam Collection](https://www.kaggle.com/uciml/sms-spam-collection-dataset)

### Dataset Structure

The dataset is structured with two columns:

1. **Label (Category):** Indicates whether the SMS is 'spam' or 'ham.'
2. **Message (SMS Text):** The actual content of the SMS message.

## Model Training
   - Load and preprocess the SMS dataset.
   - Split the dataset into training and testing sets.
   - Tokenize and vectorize the SMS messages using TF-IDF or another suitable method.
   - Train the machine learning model using a chosen algorithm (e.g., Naive Bayes, SVM).
   - Evaluate the model on the testing set and display performance metrics.
     
## Evaluation and Results
![Screenshot 2024-01-24 043914](https://github.com/yasonukan/Data-Science-Academy-Project/assets/73828987/82bd77b2-a7e6-4ee6-bba5-798c4a7be0df)
![output](https://github.com/yasonukan/Data-Science-Academy-Project/assets/73828987/09eb6a7c-09ad-4e68-9ace-ce5d5b3cd6f6)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

