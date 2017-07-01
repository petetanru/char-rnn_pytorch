# Text Generation Char-RNN with Pytorch
Let's try to implement [Andrej's minmal char-RNN](https://gist.github.com/karpathy/d4dee566867f8291f086) to generate text in Pytorch! The difference is that we'll use LSTM layers instead of vanilla RNN, and we'll do it in batches with GPU.

Why Pytorch? I have also implemented this in Keras with Tensorflow as backend and Pytorch is around 3x faster.

Compared to the [Intermediate RNN tutorials on Pytorch's website](http://pytorch.org/tutorials/), the main difference is that this implementation takes advantage of the GPU, by taking in multiple words/characters at a time, and in batches.

Click [here to check it out!](https://github.com/petetanru/char-rnn_pytorch/blob/master/char-rnn-example.ipynb)