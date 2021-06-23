# KaggleFashionCVAE
Hey everyone! My name is Alvin Li. I am an MIT undergraduate student studying computer science and working as a deep learning researcher in the MIT Computer Science and Artificial Intelligence Lab (CSAIL). This repository documents how I used Tensorflow to build, train, and deploy a deep feature variational autoencoder network on over 40,000 RGB images from the Kaggle Fashion Dataset. The novel architecture I developed uses a pretrained perceptual loss network (EfficientNet) to generate higher quality reconstructions than a standard convolutional VAE.

After implementing the deep feature VAE network, I used the t-distributed stochastic neighbor embedding (t-SNE) algorithm to embed the high dimensional data onto a lower dimensional space and generated a visualization of the latent space. I also generated a series of grids and interactive sliders that display a smooth linear interpolation of the images and their respective reconstructions across the learned latent space. 

The ultimate goal of this project was to build the technology behind an ML tool that powers enhanced customer search queries through scraping online retail data sources (ie. Amazon, Nordstrom, Nike, Target, Walmart). This Github repository captures the proof of concept for this product.

Take a look at the Jupyter Notebook to see the results!
