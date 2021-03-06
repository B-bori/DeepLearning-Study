# DeepLearning-Study
This repository is source forge for deep learning study held in KAIST, Mathematical Problem Solving Club in 2019 winter semester.

For those who are not attending this study, but would like to use this repository for your deep learning self study, I separated theoritical parts to lecture notes and practical parts to jupyter notebook practices. I recommend looking both, but it would be enough to see only one.

## How-to
We will use pytorch as basic tools. Large parts of code will be jupyter notebook.

## Tentative Schedule
1. Introduction : What is DL? [Lecture1](https://github.com/mekty2012/DeepLearning-Study/blob/master/LectureA1/LectureA1.pdf) [Practice1](https://github.com/mekty2012/DeepLearning-Study/blob/master/LectureA1/ExA1.ipynb)
2. MLP : Introduction and Implementation [Lecture2](https://github.com/mekty2012/DeepLearning-Study/blob/master/LectureA2/LectureA2.pdf) [Practice2](https://github.com/mekty2012/DeepLearning-Study/blob/master/LectureA2/LectureA2_1.ipynb)
3. MLP : Advanced [Practice3](https://github.com/mekty2012/DeepLearning-Study/blob/master/LectureA2/ExA2_2.ipynb)
4. SGD : Introduction and advanced SGD [Lecture3](https://github.com/mekty2012/DeepLearning-Study/blob/master/LectureA3/LectureA3.pdf) [Practice3](https://github.com/mekty2012/DeepLearning-Study/blob/master/LectureA3/ExA3.ipynb)
5. Hyperparameter Tuning and How to experiment [Lecture4](https://github.com/mekty2012/DeepLearning-Study/blob/master/LectureA4/LectureA4.pdf)
6. CNN : Introduction and Implementation [Lecture5](https://github.com/mekty2012/DeepLearning-Study/blob/master/LectureA5/LectureA5.pdf)
7. CNN : Advanced
8. RNN : Introduction and Implementation [Lecture6](https://github.com/mekty2012/DeepLearning-Study/blob/master/LectureA6/LectureA6.pdf)
9. RNN : Advanced
10. Further study : Other networks [Lecture7](https://github.com/mekty2012/DeepLearning-Study/blob/master/LectureA7/LectureA7.pdf)
11. Further study : Other methods
12. Individual Presentation

## Detailed Plan

### Introduction
- Difference between AI/ML/DL
- What we will study?
- Problems in DL : Classification, Clustering, Generative Model
- Feed Forward and Backpropagation
- Hidden theory for DL : Universal Approximation Theorem
- How torch works

### MLP
- What is MLP?
- What is Activation Function?
- What is loss function?
- Simple example using MLP : MNIST
- Batchnorm and Dropout
- Weight Initilization

### SGD
- Momentum
- Adagrad
- Adadelta
- RMSProp
- Adam
- L-BFGS
- Non Gradient Descent optimizer
  - Genetic Algorithm
- Use of lr scheduler

### Experiment
- Cross Validation
- Lasso/Ridge Regularization
- Hyperparameter Tuning
  - Grid Tuning
  - Random Tuning
  - Bayesian optimization
- Collecting data
  - Preprocessing
  - Benchmarks
  - Data Mining
- Tensorboard

### CNN
- What is CNN?
- Why CNN > MLP
- Simple example using CNN : MNIST, CIFAR10, CIFAR100
- Reception
- Residual

### RNN
- What is RNN?
- Why RNN > MLP
- Simple example using RNN : PTB, TIMIT
- LSTM
- GRU
- Attention

### Other networks
- Graph Convolutional Neural Network
- Memory Augmented Neural Network
- Deconvolutional Neural Network
- Modular Neural Network
- How to implement user-defined layer & loss

### Other methods
- Reinforcement Learning
- Semi-supervised Learning
- GAN

### Presentation
- Find some papers from NIPS, ICCV, SIGGRAPH, ICML, IEEE, ICLR, AAAI

## Thanks to
[Deeplearning StandAlone](https://github.com/heartcored98/Standalone-DeepLearning)

[Tensorflow Korea Paper Reading](https://www.youtube.com/playlist?list=PL0oFI08O71gKjGhaWctTPvvM7_cVzsAtK)
## References
[Reinforcement Learning](https://pytorch.org/tutorials/intermediate/reinforcement_q_learning.html)

[Bayesian Optimization](http://research.sualab.com/introduction/practice/2019/02/19/bayesian-optimization-overview-1.html)

[Attention](https://arxiv.org/abs/1706.03762)
