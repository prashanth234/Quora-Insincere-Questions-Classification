# Quora-Insincere-Questions-Classification

This project is about predicting whether a question asked on Quora is sincere or not.

Used Glove embeddings on 1306122 records in train data. 

Trained on sequential model consisting of Bidirectional LSTM, Dropout, Conv1D, MaxPooling1D layers using Tensorflow.

Training accuracy: 0.9628%

Test accuracy: 0.66438 (F1 Score)
