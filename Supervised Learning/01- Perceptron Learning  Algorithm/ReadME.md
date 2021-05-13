# Perceptron Learning ALgorithm (PLA)

## What is the Perceptron?

The Perceptron is one of the simplest ANN architectures, invented in 1957 by Frank Rosenblatt. It is based on a slightly different artificial neuron.
The inputs and output are now numbers (instead of binary on/off values) and each input con‐nection is associated with a weight. The TLU computes a weighted sum of its inputs (z = w_1 x_1 + w_2 x_2 + ⋯ + w_n x_n = x^T w), then applies a step function to that sum and outputs the result: h_w(x) = step(z), where z = x^T w.The picture below is a threshold logic unit (TLU).

![TLU](https://i.imgur.com/LMWE5cc.png)

## How does the Perceptron?

A Perceptron is simply composed of a single layer of TLUs,6 with each TLU connected to all the inputs. When all the neurons in a layer are connected to every neuron in the previous layer (i.e., its input neurons), it is called a fully connected layer or a dense layer. To represent the fact that each input is sent to every TLU, it is common to draw special passthrough neurons called input neurons: they just output whatever input they are fed. All the input neurons form the input layer. Moreover, an extra bias feature is generally added (x0 = 1): it is typically represented using a special type of neu‐ron called a bias neuron, which just outputs 1 all the time. A Perceptron with two inputs and three outputs is represented below. This Perceptron can classify instances simultaneously into three different binary classes, which makes it a multi‐output classifier.

![](https://i.imgur.com/nQCsFs8.png)

More details can be found in my notebook, along with an example of how  PLA works using Julia and the iris data set.
