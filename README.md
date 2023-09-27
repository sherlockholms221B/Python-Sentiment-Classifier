# Sentiment Analysis with Naive Bayes Classifier

This Python codebase contains a sentiment analysis implementation using a Naive Bayes classifier. It is designed to classify text data as either positive or negative sentiment based on the words used in the text. The classifier has been trained on the IMDb reviews dataset.

## Prerequisites

Before running the code, ensure you have the following prerequisites:

- Python 2.7
- Required Python libraries (see `requirements.txt`)

## Usage

1. Clone the repository to your local machine.

2. Make sure you have the required libraries installed by running:

3. Run the `train()` function to train the Naive Bayes classifier on the IMDb reviews dataset.

4. Use the `classify(text)` function to classify a text as either positive or negative sentiment. You can integrate this function into your own projects for sentiment analysis.

## Code Structure

- `train()`: Function to train the Naive Bayes classifier on the IMDb reviews dataset.

- `classify(text)`: Function to classify a text as positive or negative sentiment.

- `negate_sequence(text)`: Function to detect negations in text and transform negated words into "not\_" form.

- `MI(word)`: Function to compute the weighted mutual information of a term.

- `feature_selection_trials()`: Function to perform feature selection by selecting the top k features based on mutual information.

## Testing

The code includes functions for testing the classifier's accuracy on the Pang Lee dataset. You can uncomment the relevant lines in the `__main__` section to test the classifier's performance.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The code is based on the principles of Naive Bayes classification and sentiment analysis.
- The IMDb reviews dataset was used for training the classifier.

Feel free to use and modify this code for your own sentiment analysis projects.
