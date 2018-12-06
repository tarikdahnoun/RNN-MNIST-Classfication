# RNN-MNIST-Classfication
Using Recurrent Neural Networks (RNNs)

We use RNNs to design a classifier that works with Keras' MNIST data set. The RNN classifies a handwritten number to a digit. There are four architectures, taken over 10 epochs.

Method 1: 3 Stacks of Simple RNN Method 2: 3 Stacks of Long Short Term Memory (LSTM) Method 3: 3 Stacks of Gated Recurrent Unit (GRU) Method 4: 1 Stack of each algorithm (Simple RNN, LSTM, GRU)

Despite the odd architecture of Method 4, it results in the highest accuracy (~ 99.5%) on the validation set.
