# Deep Learning 
<img width="95" src="https://github.com/ttungl/Deep-Learning-Google/blob/master/Lesson1/googlelogo.png"> <img width="85" src="https://github.com/ttungl/Deep-Learning-Google/blob/master/Lesson1/tensorflow.png">

This is the online course on [Udacity](https://www.udacity.com/course/deep-learning--ud730).

Instructor: [Dr. Vincent Vanhoucke](https://research.google.com/pubs/VincentVanhoucke.html) from Google Brain.

Notice: The original assignments can be found at this [link](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/examples/udacity).

### * Logistic Regression, Stochastic Optimization, and Data & parameters tuning. 
* [notMNIST - Deep Learning with Tensorflow](https://github.com/ttungl/Deep-Learning-by-Google/blob/master/Lesson1/DeepLearning_assignment_1.ipynb). 

### * Deep Neural Networks
* [Implemented a fully connected network using SGD and ReLUs with Tensorflow](https://github.com/ttungl/Deep-Learning-Google/blob/master/Lesson1/2_fully_connected_network_using_SGD.ipynb)
              
### * Regularization
* [Implemented a multi-layer neural network using ReLUs, L2-regularization, and dropout, to prevent overfitting](https://github.com/ttungl/Deep-Learning-Google/blob/master/Lesson1/3_Regularization.ipynb).
  
### * Convolutional Networks
* Reading: 
  + C. Olah, [Conv Nets: A Modular Perspective](http://colah.github.io/posts/2014-07-Conv-Nets-Modular/). 
  + C. Olah, [Understanding Convolutions](http://colah.github.io/posts/2014-07-Understanding-Convolutions/).  
  + C. Olah, [Calculus on Computational Graphs: Backpropagation](http://colah.github.io/posts/2015-08-Backprop/).
  + V. Dumoulin and F. Visin, [A guide to convolution arithmetic for deep learning](https://arxiv.org/pdf/1603.07285.pdf). (arXiv, March 2016). 
* [Implemented a convolutional neural network](https://github.com/ttungl/Deep-Learning-Google/blob/master/Lesson1/4_Convolutional_Neural_Networks.ipynb).

### * Deep Models for Text and Sequences
#### [Embeddings]
* Reading:
  + T. Mikolov et al., [Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/pdf/1301.3781.pdf). (arXiv, Sep 2013).
  + T. Mikolov et al., [Distributed Representations of Words and Phrases and their Compositionality](https://arxiv.org/pdf/1310.4546.pdf). (arXiv, Oct 2013). `Subsampling` and `Negative sampling` in Word2Vec.
* Implemented a Word2Vec with the skip-gram model and CBOW model in different datasets of Wikipedia text as follows: 
  + With [text8.zip dataset](https://github.com/ttungl/Deep-Learning-Google/blob/master/Lesson1/5_WordToVec.ipynb).
  + With [enwik8.zip dataset](https://github.com/ttungl/Deep-Learning-Google/blob/master/Lesson1/5_WordToVec_enwik8.ipynb).
 
#### [Recurrent Neural Networks]
* Reading:
  + [Understanding LSTM networks](http://colah.github.io/posts/2015-08-Understanding-LSTMs/) 
  + H. Sak et al., [Long Short-Term Memory Based Recurrent Neural Network Architectures for Large Vocabulary Speech Recognition](https://arxiv.org/pdf/1402.1128v1.pdf). (arXiv, Feb 2014).
* [LSTM: Long Short-Term Memory](https://github.com/ttungl/Deep-Learning/blob/master/Lesson1/6_LSTMs.ipynb)
  + Note: Backprop for RNNs example can be found at these links [[1]](http://peterroelants.github.io/posts/rnn_implementation_part01/) and [[2]](http://www.wildml.com/2015/10/recurrent-neural-network-tutorial-part-4-implementing-a-grulstm-rnn-with-python-and-theano/).
  + [char-LSTM implementation with numpy](http://blog.varunajayasiri.com/numpy_lstm.html)

#### [Resources]
* [Book] [Deep Learning with Python](https://www.manning.com/books/deep-learning-with-python?a_aid=keras&a_bid=76564dff), Nov 2017 by [François Chollet](https://twitter.com/fchollet)
