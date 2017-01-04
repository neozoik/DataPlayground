


# Data Playground ()
Data Science solutions Playground


**Machine Learning implementation example** 
(incomplete personal GPS Data from last 2 years)

DataExampleUno []

[RawData](https://http://bit.ly/2hN3t1S/)
[PreProcessedData](https://http://bit.ly/2hN3t1S/)

List of pre-processing method to implement: 
Cluster analysis[day of week, part of day, movement speed, chaotic/ordered] 
Dimensionality reduction [linear mapping]
  
List of ML techniques to implement

 - Anomaly detection  
 - Structured prediction  
 - Reinforcement learning
 - Supervised learning

# List of NNs 
  

 1. CNN convolutional neural network, context recognition [https://colah.github.io/posts/2014-07-Conv-Nets-Modular/][https://colah.github.io/posts/2014-07-Understanding-Convolutions/]   
 2. LSTM Long Short Term Memory network, context recognition [https://colah.github.io/posts/2015-08-Understanding-LSTMs/]
 3. GAN Generative Adversarial Networks [http://www.kdnuggets.com/2017/01/generative-adversarial-networks-hot-topic-machine-learning.html]

  
# Visualization for 
[https://colah.github.io/posts/2015-01-Visualizing-Representations/]

 - CV 
 - LinkedIn 
 - Article
 - Training process visualization 
 - Dataset visualization 
 - Working trained NN visualization
 - Illustration of the architecture

# Supervised learning - convolutional neural network CNN
> Point is to pretrain CNN on pre-labeled data for context activity recognition.

# Structured prediction - generative adversarial network GAN
> GANs solve a problem by training two separate networks with competitive goals.One network produces prediction for walking route  (generative) another network distinguishes between the real path and the generated route (adversarial).
The concept it to train these network competitively, so that after some time, neither network can make further progress against the other. Or the generator becomes so effective that the adversarial network can not distinguish between real and synthetic solutions, even with unlimited time and substantial resources.
GANs will be used to draw walking route, given an desirable category and a random rule:
“draw me a evening walking route, and it can’t be one of the paths that I walked before.”

# Anomaly detection - long short term memory network LSTM 
> One of the appeals of RNNs is the idea that they might be able to connect previous information to the present task, such as using previous walking route might inform the understanding of the future destination.
Sometimes, we only need to look at recent information to perform the present task. For example, consider a movement model trying to predict the next destination based on the previous ones. If we are trying to predict the last point in stable sequence we don’t need any further context – it’s pretty obvious the next point is going to be as usual. In such cases, where the gap between the relevant information and the place that it’s needed is small, RNNs can learn to use the past information.
Unfortunately, as that gap grows, RNNs become unable to learn to connect the information.
Long Short Term Memory networks – usually just called “LSTMs” – are a special kind of RNN, capable of learning long-term dependencies. They work tremendously well on a large variety of problems, and are now widely used.
LSTMs are explicitly designed to avoid the long-term dependency problem. Remembering information for long periods of time is practically their default behavior, not something they struggle to learn!
