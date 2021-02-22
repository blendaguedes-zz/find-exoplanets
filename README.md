<h1> Discovering Exoplanets </h1>

This project was made to complete the credits for the discipline of Neural Networks in the master's program in Applied Computing at PPGIA/UFRPE. 
Como tive que apresentar um experimento e um artigo, este repositório mostrará os dois trabalhos. 

<h3>Introduction</h3>

In 2009 the Kepler Space Observatory was launched by NASA, with the aim to answer the question: ”How frequent are other Earths in our galaxy?” [2]. The observatory is on its second mission since 2014, and had labeled more than 10, 000 possible exoplanets [3].

Kepler scanned 1,284 new exoplanets in 2016. As in 2017, there were more than 3,000 exoplanets confirmed in total (using all detection meth- ods, including ground-based ones). The observatory still works and keep on searching for other exoplanets [3].

Our goal with this project is to use the data collected by the Kepler Space Observatory during all these years and build a Neural Networks model solution that, given the characteristics collected by Kepler, is feasible to identify exoplanets.

<h3>Multilayer Perceptron</h3>

Multilayer Perceptron (MLP) type RNA is a type of supervised net- work that uses a set of perceptron and direct feed 1. Its basic structure is called in three points: each neuron has a function of activation nonlinear and differentiable; there are one or more layers (see Figure 4) intermediate or hidden for both input and output layers; and has a high number of con- nections where their amplitudes are calculated by the weight of each of the connections.
The input and output layers work similarly to a perceptron, this time having their connections pointed at more than one neuron. The intermediate layers work with a network of perceptrons, having exits of a neuron in any layer with the entrance of the neurons of the following layer. Finally the output layer delivers the result of the network.
The Backpropagation technique is used to adjust the weights of the net- work connections. This technique uses with parameter the network prediction error propagating this error retroactively, so it receives this name.
The weight adjustment is done using the Generalized Delta Rule which is an adaptation of the Delta Rule. [7], where the network weights are suitable through the descending gradient:

<h3>Methodology</h3>

The machine used was a MacBook Pro 2017, with a Mac OS Mojave operating system, 500Gb SSD, RAM 16Gb, processor of 2.9 GHz Quad-Core Intel Core i7.
The programming language used was Python 3 and PyTorch [9] library was used to built the Neural Networks.

<h4>Database</h4>

The database was taken by the Kaggle [3] platform. And the data cleaning was based in the work referenced in [10]. After that we have 7803 samples. It was divided in three parts where 70% was to training, 15% to validation and 15% to testing. The features were normalized using min-max scaling.
Finally we had 37 different characteristics to use as a input and a binary output.

<h4>Neural Network Configuration</h4>

Five different Neural Network were built, Table 1 has all the Neural Net- works configurations:
