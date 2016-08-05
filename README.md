


# Questions

* Is it possible to write the whole system as one loss function we are minimising?
* Do we train the generative net on its reconstruction error, or only backpropagated signals through the discriminative net?
* Training on noise, seems like a waste, is there a better way?
* of course. Cant update the generative net based on gradients from random sample and discrim, the generative net is not even involved...
* How does the loss function ( CE(1-D(G(z))) + CE(D(z)) ) relate to minimax?
* What is the difference between training the two nets jointly on the same loss function and training them independently?
* How do I make a linear version with convex loss? Analytical analysis of GAN siilar to Baldi/Saxe?
* What if we first train a vanilla autoencoder, and then initialise the discriminator and generator with that autoencoder?