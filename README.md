# VAE_Variational_Autoencoders

How to generate new data in Machine Learning with VAE (Variational Autoencoder) applied to Mnist with Python code
The Variational AutoEncoders are Neural Networks used to generate new data (Unsupervised Learning). This model is used for generating new data for the dataset or also in case we want to cancel the noise from our data. The Networks is composed by multiple Neural Networks: an encoder and a decoder connected by a bottleneck that is the latent space.

The Encoder process the data till the bottleneck (Latent space) reducing the size and the Decoder take the data and and reconstruct the data structure to give the same output as our original data. We can see the latent space as a representation of our data.

In this specific case, we are reading numbers (Mnist Dataset) images of 28x28 pixels (784 elements), we want to reduce them to 32 elements (latent space) recreating than again the image of 28x28 pixels.
The MNIST dataset is a large collection of handwritten digits that is commonly used for in image processing.
