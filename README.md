# Airline-Sentian--Sentiment-Analysis-using-Text-Classification

This project focuses on the automated detection of sentiment from various textual comments and feedback related to airlines. Using Machine Learning and Deep Learning techniques, the project classifies sentiments into categories such as positive, negative, and neutral. It leverages Keras, TensorFlow, and LSTM networks for building the classification model.

# Overview 
Twitter is widely accessible social network and heavily used to express individual thoughts on specific topics online. It can be regarded as a valuable source to gather information on user opinions concerning certain issues. 

The data set contains US airline tweets labelled according to their sentiment. The data has been processed in order to train a deep neural network (DNN) that serves as a text sentiment classifier model. The aim is to evaluate the performance of a custom trained word vectorization approach in the context of pre-processing and dimension reduction for tweet text analysis. In addition, the final model is applied to recently extracted tweet data related to a selected US airline to demonstrate the model performance in real-world use cases.

With the growth of online reviews and customer feedback, it has become crucial for businesses, especially in the airline industry, to analyze sentiment effectively. This project aims to classify customer feedback into different sentiment categories using text classification techniques.

The model is built using Keras and TensorFlow, with an LSTM (Long Short-Term Memory) neural network for sentiment analysis. LSTMs are known for their efficiency in processing sequential data like text, making them ideal for this task.

# Model Architecture
The model uses a deep learning approach with an LSTM network. 
Keras based Model Pipeline -LSTM Network
LSTM stands for Long Short Term Memory Networks.LSTM networks work well with time-series data

The architecture includes:

Embedding Layer: For text vectorization.
LSTM Layer: To capture sequential dependencies in the text data.
Dense Layer: For classification output.

The LSTM network is trained on the labeled data to classify sentiments into the appropriate categories.


# Components: 
1. Tokenizer: Converts text into sequences of integers, where each integer represents a word in the dataset vocabulary.
2. Sequential: A linear stack of layers that allows you to build a model layer by layer.
3. LSTM (Long Short-Term Memory): A type of recurrent neural network (RNN) that is excellent for capturing long-term dependencies in sequence data like text.
4. Dense: A fully connected layer where each input neuron is connected to every output neuron, used for final classification.
5. Dropout: A regularization technique that randomly drops neurons during training to prevent overfitting.
6. SpatialDropout1D: Similar to Dropout but drops entire 1D feature maps instead of individual neurons, used in text data to promote generalization.
7. Embedding: Converts words into dense vector representations, allowing the model to learn relationships between words.

 

# Outcome
The sentiment analysis model gives the predicted output as positive or negative based on the sentiment in the input text.



