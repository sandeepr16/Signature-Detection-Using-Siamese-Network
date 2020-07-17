# Signature-Detection-Using-Siamese-Network
Siamese network has a stack of convolutional and pooling layers and a final fully connected layer with 128 neurons. The sister network takes on the same weights and biases as the original network (essentially means running the same network twice). It takes the input image pair and produces two 128-D vectors as outputs. The network learns to encode similar input images closer and dissimilar ones, farther apart from each other in the vector space. The conventional method to train it is by using a contrastive loss function or a triplet loss that takes three images at once.


Siamese COnvolutional NEtwohttps://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf
