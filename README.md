# Email/SMS Spam Classifier

**Email/SMS Spam Classifier** is a machine learning model designed to accurately classify text messages as either spam or legitimate (ham). The model leverages various machine learning algorithms to achieve high accuracy in identifying spam messages.

## Project Overview

The primary goal of this project is to build a reliable and efficient spam classifier for emails and SMS messages. By training the model on a labeled dataset, it can predict whether a given message is spam or not.

### Key Features

- **High Accuracy**: Achieved 97% accuracy and 100% precision using Multinomial Naive Bayes (MNB), outperforming other models.
- **Model Comparisons**: Evaluated multiple algorithms including Gaussian Naive Bayes (GNB), Bernoulli Naive Bayes (BNB), Support Vector Machine (SVM), K-Nearest Neighbors Classifier (KNC), and Logistic Regression (LR).
- **Kaggle Dataset**: Utilized a publicly available dataset consisting of 5,574 English messages, labeled as "ham" (legitimate) or "spam".

## Dataset

The dataset used in this project is sourced from Kaggle and contains 5,574 SMS and email messages. Each message is labeled as either "ham" (legitimate) or "spam". The dataset is preprocessed and ready for training and testing.

## Models and Techniques

Several machine learning algorithms were employed to build and evaluate the spam classifier:

- **Multinomial Naive Bayes (MNB)**: Achieved the best results with 97% accuracy and 100% precision.
- **Gaussian Naive Bayes (GNB)**
- **Bernoulli Naive Bayes (BNB)**
- **Support Vector Machine (SVM)**
- **K-Nearest Neighbors Classifier (KNC)**
- **Logistic Regression (LR)**

### Performance Metrics

- **Accuracy**: The percentage of correctly classified messages.
- **Precision**: The percentage of correctly classified spam messages out of all messages classified as spam.

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/NitinGautam05/Email-SMS-spam-detection.git
   ```

## Results

The Multinomial Naive Bayes (MNB) model outperformed other models, achieving:

- **Accuracy**: 97%
- **Precision**: 100%

## Contributing

Contributions are welcome! Feel free to fork this repository, open an issue, or submit a pull request.

## Contact

If you have any questions or suggestions, please reach out via email or open an issue on GitHub.
