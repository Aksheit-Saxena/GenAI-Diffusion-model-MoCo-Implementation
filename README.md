# GenAI-Diffusion-model-MoCo-Implementation

What are the problems the code solves?

1.  Construct a DDPM on the animal face data. Experiment with three different values of backward inference time- Plot a grid of 10by 10 images for all three cases and compute the FID. Use VAE to implement a class-conditional DDPM on its latent space. Use classifier guidance with the score-based formulation.

2.   Implement Self-supervised learning using Momentum Contrast Encoder method (MoCO). Try 3 sets of augmentation methods. Implement a linear classifier on the learnt representations. Compare it witha full-blown CNN, that has the same number of parameters. Record the reduction in the amount of supervised data needed

Dataset Used: https://www.kaggle.com/datasets/andrewmvd/animal-faces
Complete details of the code along with the results can be found in the jupyter notebook.


