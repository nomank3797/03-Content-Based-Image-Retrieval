# 03-Content-Based-Image-Retrieval
This repository consists of three Python driver scripts:

train_autoencoder.py: Trains an autoencoder on the MNIST handwritten digits dataset using the ConvAutoencoder CNN/class
index_images.py: Using the encoder portion of the trained autoencoder, we’ll compute feature vectors for each image in the dataset and add the features to a searchable index
search.py: Queries our index for similar images using a similarity metric
Our output/ directory contains the trained autoencoder and index. Training also results in a training history plot and visualization image that can be exported to the output/ folder.
