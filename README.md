## IMDb Movie Review Sentiment Analysis using RNN

### Project Overview

This project develops a Sentiment Analysis system using a Recurrent Neural Network (RNN) to automatically classify IMDb movie reviews as Positive or Negative.

The model learns the sequential relationships between words in a review and uses these patterns to predict the sentiment of unseen movie reviews.

⸻

### Objective

The main objective of this project is to:

* Analyze movie reviews using Deep Learning.
* Understand sequential relationships between words.
* Build an RNN-based binary classification model.
* Classify reviews as Positive or Negative.
* Evaluate the model using standard classification metrics.

⸻

### Dataset

The project uses the IMDb Movie Reviews Dataset available through TensorFlow/Keras.

* Total Reviews: 50,000
* Training Reviews: 25,000
* Testing Reviews: 25,000
* Classes: Positive and Negative

Sentiment Labels

Label	Sentiment
0	Negative
1	Positive

⸻

### Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

⸻

### Model Architecture

The RNN model consists of:

IMDb Reviews  
      -
Tokenization
      -
Padding
      -
Embedding Layer
      -
Simple RNN
      -
Dense Layer
      -
Sigmoid Activation
      -
Positive / Negative

### Model Layers

* Embedding Layer – Converts word IDs into numerical vector representations.
* SimpleRNN Layer – Learns sequential relationships between words.
* Dense Layer – Performs the final binary classification.
* Sigmoid Activation – Produces a probability for the sentiment.

⸻

### Data Preprocessing

The reviews are prepared before training using:

1. Tokenization
2. Numerical encoding
3. Sequence padding
4. Train-test splitting

The maximum sequence length is set to 200 words.

⸻

### Model Evaluation

The model performance is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

Training and validation Accuracy and Loss are also visualized using graphs.

⸻

### Sample Prediction

Input

This movie was amazing and I really loved it.

Output

Sentiment: Positive

The trained model can also classify new unseen movie reviews as Positive or Negative.

⸻

### Results

The trained RNN model successfully performs binary sentiment classification on IMDb movie reviews.

The final performance can be analyzed using the Accuracy, Precision, Recall, F1-Score and Confusion Matrix generated in the notebook.

⸻

### Future Improvements

The project can be further improved by:

* Using LSTM or GRU networks.
* Comparing RNN, LSTM and GRU performance.
* Using Bidirectional RNNs.
* Applying advanced text preprocessing techniques.
* Developing a web application for real-time sentiment prediction.

⸻

### Conclusion

The RNN-based sentiment analysis system successfully classified IMDb movie reviews into positive and negative sentiments. By learning the sequential relationships between words, the RNN was able to understand important patterns in movie reviews. The model was evaluated using accuracy, precision, recall, F1-score, and confusion matrix. This project demonstrates how Recurrent Neural Networks can be effectively used for text classification and sentiment analysis.
