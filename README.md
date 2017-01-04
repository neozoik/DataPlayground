# DataPlayground
Data Science solutions Playground

Machine Learning implementation example (incomplete personal GPS Data from last 2 years)

DataExampleUno []
LinkToDataSet 
  [[http://bit.ly/2hN3t1S], PreProcessedData]
List of pre-processing method to implement 
  [Cluster analysis[day of week, part of day, movement speed, chaotic/ordered], Dimensionality reduction [linear mapping]]
List of ML techniques to implement 
  [Anomaly detection, Structured prediction,Reinforcement learning,Supervised learning]
List of NNs 
  [CNN(context recognition, IR), LSTM(context recognition, AR),Generative Adversarial Networks GAN ]
Visualization for CV, LinkedIn and article 
training process visualization
dataset visualization
working trained NN visualization
illustration of the architecture





Supervised learning (pretrain CNN on pre-labeled data for context recognition )
*Generative Adversarial Networks GAN* 
GANs solve a problem by training two separate networks with competitive goals.
one network produces answers (generative)
another network distinguishes between the real and the generated answers (adversarial)
The concept it to train these network competitively, so that after some time, neither network can make further progress against the other. Or the generator becomes so effective that the adversarial network can not distinguish between real and synthetic solutions, even with unlimited time and substantial resources.
The details are interesting, but let’s put those aside for now. GANs are being used to draw images, given an image category and a random seed:
“draw me a woodpecker, and it can’t be one of the woodpeckers that I showed you before.”
