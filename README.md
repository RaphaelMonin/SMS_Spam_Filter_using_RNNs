# SMS spams filter using RNNs

Using a dataset of 5572 SMSs labeled spam or ham.

I compared the performances of four recurrent neural networks to filter spams.

Both LSTM and GRU neural network reach 97.5% of accuracy but are very unstable.

A bidirectionnal LSTM neural network reach 97.5% too but is much more stable.

A bidirectionnal GRU neural network gives the best results with 98% of accuracy plus a great stability.
