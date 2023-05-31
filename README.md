# Spam Classifier

This repository contains code for a spam classifier that uses three different models: Artificial Neural Network (ANN), SimpleRNN, and Naive Bayes. The models are trained on labeled email data to classify incoming messages as either spam or not spam.

## Models Used

1. Artificial Neural Network (ANN): The ANN model is implemented using TensorFlow and Keras. It consists of multiple layers of artificial neurons and is trained to classify spam based on input features derived from email content.

2. SimpleRNN: The SimpleRNN model is a type of Recurrent Neural Network (RNN) that can capture sequential information from text data. It is implemented using TensorFlow and Keras, and it learns to classify spam by considering the order of words in the email.

3. Naive Bayes: The Naive Bayes model is a probabilistic classifier based on Bayes' theorem. It is implemented using scikit-learn and is trained to classify spam by estimating the probability of an email being spam or not based on the occurrence of certain words or features.

## Dataset

The spam classifier is trained on a labeled email dataset. The dataset contains a collection of emails, each labeled as spam or not spam. It is preprocessed to extract relevant features from the email content, such as word frequencies or TF-IDF values.

## Usage

To use the spam classifier, follow these steps:

1. Clone the repository:


2. Install the required dependencies:


3. Prepare your data:

   - Ensure your email dataset is properly formatted with labels indicating spam or not spam.
   - Preprocess the data to extract relevant features (e.g., word frequencies or TF-IDF values).

4. Train the models:

   - Adjust the model parameters (if needed) in the respective Python files (e.g., `ann_model.py`, `simplernn_model.py`, `naive_bayes_model.py`).
   - Run the training scripts for each model:


5. Evaluate the models:

- After training, the models will be saved with their respective weights or parameters.
- Use the evaluation script to assess the performance of each model:


6. Make predictions:

- Use the trained models to make predictions on new email data using the prediction script:


## Contributing

Contributions to improve the spam classifier or add new models are welcome. If you encounter any issues or have suggestions, please open an issue or submit a pull request.



