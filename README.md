# SMS spam filter using RNNs

### Overview

I compared the performances of four recurrent neural networks to filter spams.
- a Long Short-Term Memory (LSTM) neural network
- a Gated Recurrent Unit (GRU) neural network
- a bidirectionnal LSTM neural network
- a bidirectionnal GRU neural network

### Results

Both LSTM and GRU neural network reach 97.5% of accuracy but are very unstable.

A bidirectionnal LSTM neural network reaches 97.5% too but is much more stable.

A bidirectionnal GRU neural network gives the best results with 98% of accuracy plus a great stability.

### Dataset

SMS Spam Collection Dataset from UCI Machine Learning: https://www.kaggle.com/uciml/sms-spam-collection-dataset

It contains one set of SMS messages in English of 5,574 messages, labeled ham (legitimate) or spam.

### Usage

Run this using jupyter notebook. Just type jupyter notebook in the main directory and the code will pop up in a browser window.
