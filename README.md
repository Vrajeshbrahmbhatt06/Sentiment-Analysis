# Sentiment Analysis

This project demonstrates a small-scale sentiment analysis system using Python for identifying the sentiment (positive, negative, or neutral) of a given piece of text. It utilizes machine learning techniques and natural language processing (NLP) libraries to perform sentiment analysis on textual data.

## Features

- Data Preprocessing: The text data is preprocessed by converting labels to string format, lowercasing, removing punctuation, and lemmatizing the words to standardize the text and reduce noise.
- Model Development: A Linear Support Vector Classifier (LinearSVC) model from the scikit-learn library is employed for sentiment analysis. LinearSVC is known for its performance on text classification tasks.
- Model Evaluation: The dataset is split into training and testing sets. Metrics such as accuracy, precision, recall, and F1-score are used to evaluate the model's performance on the testing set.

## Dataset

The Twitter Sentiment Dataset (available at [https://www.kaggle.com/datasets/saurabhshahane/twitter-sentiment-dataset](https://www.kaggle.com/datasets/saurabhshahane/twitter-sentiment-dataset)) is used for this project. This dataset provides a diverse collection of tweets labeled with sentiments, allowing the model to be trained and evaluated effectively.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/sentiment-analysis.git`
2. Install the required dependencies
3. Run the main script: `python main.py`

## Results

The model achieves an accuracy of 84.82%, precision of 84.86%, recall of 84.82%, and F1-score of 84.74% on the testing set. These metrics indicate the model's ability to accurately classify the sentiment of text data.

## Conclusion

This sentiment analysis project demonstrates the implementation of a small-scale NLP system for sentiment classification. By leveraging machine learning algorithms and NLP techniques, it offers a starting point for understanding sentiment in textual data. The code provides a clean and efficient implementation while emphasizing modularity and scalability.

## License

This project is licensed under the [GNU](https://github.com/Vrajeshbrahmbhatt06/Sentiment-Analysis/blob/main/LICENSE).

Feel free to contribute, open issues, or provide feedback to help improve this project.
