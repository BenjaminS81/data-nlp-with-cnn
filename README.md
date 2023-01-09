### Deep Learning NLP-CNN simulation with a Keras Embedding ###

In this simulation employing an example NLP dataset from tensorflow_datasets, a RNN (Recurrent neural network) layer is replaced with a CNN (convolutional neural network) layer. In this case lists of words are represented by matrices. Exactly the same way as images.

Each of the words is represented by a vector of size N (the size of the keras embedding). Therefore, as a sentence is a sequence of words, it is represented by a matrix (number of words, N). So, all sentences are actually represented as matrices once embedded.

If you run this simulation in eg. VS code, make sure to have all the latest tensorflow and keras dependencies installed, as well jupyter notebook extensions fully setup to smoothly execute the simulation. 

The simulation is highly guided step-by-step to explain what happens for each code block. If you are running into any issues, please contact me directly.


