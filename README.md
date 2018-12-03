# Keras RNN Speech Recognizer

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project is modified from the third project (VUI Speech Recognizer) of [Udacity's Natural Language Processing Nanodegree](https://www.udacity.com/course/natural-language-processing-nanodegree--nd892), which is a good introduction to do speech recognition with deep recurrent neural networks using `keras`. The dataset is the subset of [LibriSpeech](http://www.danielpovey.com/files/2015_icassp_librispeech.pdf).

## Requirements
* Python3
* keras (== 2.0.9)
* tensorflow-gpu (== 1.3.0)
* CUDA (== 10.0.130)
* cuDNN (== 6.0.21)

## Outline
More details are illustrated in the `.ipynb` file.
1. Acoustic Features for Speech Recognition
2. Deep Neural Networks for Acoustic Modeling
   * Model 0: RNN
   * Model 1: RNN + TimeDistribute Dense
   * Model 2: CNN + RNN + TimeDistributed Dense
   * Model 3: Deeper RNN + TImeDistributed Dense
   * Model 4: Bidirectional RNN + TimeDistributed Dense
   * Final Model (Deeper Bidirectional RNN + TimeDistribute Dense)
   * Compare the Models
3. Obtain Predictions

## Tech
The tech stack I use in this project:
* [Jupyter](http://jupyter.org/) - an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. Uses include: data cleaning and transformation, numerical simulation, statistical modeling, data visualization, machine learning, and much more.
* [TensorFlow](https://www.tensorflow.org/) - an open source software library for numerical computation using data flow graphs.
* [Keras](https://keras.io/) - a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano. It was developed with a focus on enabling fast experimentation. Being able to go from idea to result with the least possible delay is key to doing good research. 

## Todos
 - Experiment with dilated convolutions and max pooling layers when incorporating a convolutional layer.
 - I use Gated Recurrent Units (`keras.layers.GRU`) in this project. Try Long Short-Term Memory (`keras.layers.LSTM`) or `keras.layers.SimpleRNN`. To see if the exploding gradients problem happens.
 - Massive dataset.
 - More epochs.
 - More complex architecture.

## License
[Keras RNN Speech Recognizer](https://github.com/yungshun317/keras-rnn-speech-recognizer) is released under the [MIT License](https://opensource.org/licenses/MIT) by [yungshun317](https://github.com/yungshun317).