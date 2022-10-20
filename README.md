# Digit-Comparaison-PyTorch

The goal of this project is to investigate the effect of
various neural network architectures and the applica-
tion of known techniques such as weight sharing to
improve the classification results for a given task, on MNIST dataset. To
illustrate the gain of each technique, various different
architectures will be presented and studied.

# Testing with the script

The test.py script can be given arguments to
change its behaviour to illustrate various part of the
project. By default, giving it no arguments will train
10 times the weight sharing + auxiliary loss network
with 25 epochs each time. At the end, it will print
the mean and standard deviations of the train and
test errors. To showcase the other network discussed
throughout the report, a first numerical argument can
be passed to the script. It determines which network
to run and can be used to support the content of this
document.

0 - Network with auxiliary losses and weight
sharing 
1 - Network with weight sharing 
2 - Baseline network 
3 - Run all networks, from baseline to weight 
sharing with auxiliary losses.
