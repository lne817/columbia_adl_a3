# Columbia University COMS W4995 Applied Deep Learning
# Nae Eoun Lee (UNI: nl2287)

## 3a. Implementation of ReLU
My own implementation of ReLU provided the higher train accuracy and the lower train loss than either of Tanh or Sigmoid. 

## 3b. Optimzer and Initializer Selection
Several optimzers (SGD, SGD with momentum, Adagrad, Adam) with a fixed learning rate (set to be 0.001 to be fast enough and still decreasing the loss) were tested for their performance. We observed that Adam, which combines both momentum and adaptive learning algorithms, performed the best. It was also demonstrated that using momentum did not make much change to SGD but provided a big boost to speed of learning, and AdaGrad accelerated the convergence by accelerating per parameter learning. For the weights on the initializer, the GlorotNormal performed the best.

## 3c. Vanishing Gradient Problem
