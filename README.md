
# Data Playground (Predictive Analytics Project Capstone) 
Here we will apply data mining techniques in a real world case study. The case study concerns nash eqilibrium in personal fitness context (walking), but the principles apply equally to any personal assestment involving individual-level correction. This repo is really a "lab" for practically testing our skills in a real world context. Facility with R or Python will be uncovered, and some familiarity with predictive modeling and time series analysis.

Note:  This course is also listed as Persuasion Analytics, the study of microtargeting and uplift modeling.  The data in the course are sizeable and complex, and the domain (political targeting) is relatively new and unlikely to be familiar to most students, hence the course is ideal as a real-world case study for analytics students who need to be prepared to apply their analytical skills to new situations.  Students who sign up for Persuasion Analytics will use curated, reduced data sets and an Excel add-in; students who are taking Predictive Analytics Project Capstone as part of their certificate program must use the full dataset and either R or Python.)

[Data Science solutions Playground]

# Data Mining in R 

Aim of Course:
In this online course, “Data Mining in R,” you will learn how to partition data and use a holdout sample, how to measure the performance of predictive models, and what to do about the problem of overfitting.  Popular classification methods (logistic regression, k-nearest-neighbors, classification trees) and prediction methods (linear regression and regression trees) are discussed.  Collaborative filtering and association rules are also covered.

This course may be taken individually (one-off) or as part of a certificate program.
Course Program:
WEEK 1: Getting Started

Data prep
Data partitioning (holdout data)
Measuring the performance of classification and prediction models
K-nearest neighbors classification

WEEK 2: Linear Regression and CART

Multiple linear regression
Classification and regression trees

WEEK 3:  Logistic Regression

Propensities and ranking

WEEK 4: Recommender Systems

Association Rules - Apriori Algorithm
Collaborative Filtering - k-Nearest neighbors

HOMEWORK:
Homework in this course consists of short answer questions to test concepts and guided data analysis problems using software.




# Anomaly Detection
Aim of Course:
In this online course, you will learn how to examine data with the goal of detecting anomalies or abnormal instances. This task is critical in a wide range of applications ranging from fraud detection to surveillance. At the end of this course you will have understood the different aspects that affect how this problem can be formulated, the techniques applicable for each formulation and knowledge of some real-world applications in which they are most effective.
This course may be taken individually (one-off) or as part of a certificate program.
Course Program:
WEEK 1: Getting started

The different aspects of anomalies
Classification-based approaches
WEEK 2: Unsupervised approaches

Clustering
Nearest-neighbour
Other statistical techniques
WEEK 3: Non-standard approaches

Information-theoretic methods
Spectral techniques
WEEK 4: Applications

Credit-card fraud
Intrusion detection
Insurance
Healthcare
Surveillance
 
HOMEWORK:
Homework in this course consists of short answer questions to test concepts and guided data analysis problems using Python. There is also an end-of-the-course data analysis project.

# Deep learning
In this online course, you will learn about the rapidly evolving field of Deep Learning. The surge in deployed applications based on concepts and methods in this field is an indication of its potential to help fully realize the promise of Artificial Intelligence. At the end of this course you will understand the basic concepts underlying the representations and methods in deep learning and see some applications where deep learning is most effective. You will also gain an appreciation of what kind of problems are most suited for this field and current research trends.
Course Program:
WEEK 1: Neural Networks and Optimization

Overview
Machine Learning Basics
Deep Feedforward Networks
Basic Optimization Algorithms

WEEK 2: Convolutional Networks and Image Processing

Convolutional Networks
Practical Methodology
Image Applications
 

WEEK 3: Recurrent Architectures and Language Processing

Recurrent Networks
Long Short Term Memory
Language Applications

WEEK 4: Advanced Topics, Research Trends

Autoencoders
Representation Learning
Deep Generative Models

HOMEWORK:

Homework in this course consists of short answer questions to test concepts, practice with using public-domain tools and some guided exercises that involve freely available data. There is also an end-of-course project.


Deep learning and its place in the learning hierarchy
 
From Deep Learning by Ian Goodfellow and Yoshua Bengio and Aaron Courville

# Persuasion Analytics and Targeting

Aim of Course:
In this online course, “Persuasion Analytics and Targeting,” you will learn you how to apply predictive modeling methods, and persuasion (uplift) models in particular.  The focus will be on targeting voters in political campaigns. You will learn which aspects of campaigns are especially important for modeling purposes, and the difference between traditional targeting methods and more recent micro-targeting techniques. The course covers what to measure and how to design surveys to measure it.  The role of experiments is discussed, and you will learn how television advertising, online advertising, and social media fit in.

Note:  This course also serves as the lab component for certificate students in the Programming for Data Science PASS Program, who will register for it as Applied Predictive Analytics.  Students will study together in the same class, but there will be more emphasis on data for the latter students.  See also the Software section.

This course may be taken individually (one-off) or as part of a certificate program.
Course Program:
WEEK 1:  Background and basic campaign concepts

Why campaigns need to target
Phases of a campaign
Finding the right targets for the right phase
Calculating the effectiveness of a voter contact
 

WEEK 2: Traditional targeting vs. individual level modeling and beginning the modeling process

Traditional targeting
Microtargeting - shifting the focus to the individual
Deciding what to predict
Survey instrument design
The modeling process
 

WEEK 3: The modeling process in detail

Common pitfalls
Missing values
Building new indicators
Evaluating models
Combining models
 

WEEK 4: Persuasion (uplift) modeling

Controlled and natural experiments
Combining A-B test with predictive modeling
Persuasion:  determining for whom the message works
Targeting for broadcast television
Targeting for online advertising




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
 - LinkedIn profile
 - Article for social media
 - Training process visualization 
 - Dataset visualization 
 - Working trained NN visualization
 - Illustration of the architecture with 

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
