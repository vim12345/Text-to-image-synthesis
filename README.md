# Text-to-image-synthesis

# Description:
Text-to-Image Synthesis is a task in which the model generates an image based on a textual description. For example, if the input is "a red apple on a table," the model will generate an image that corresponds to this description. This task typically involves generative adversarial networks (GANs) or variational autoencoders (VAEs) combined with a text encoder, such as a recurrent neural network (RNN) or transformer, to process the input text.

In this project, we will implement a basic Text-to-Image Synthesis model using GANs.
# ✅ What It Does:
* Uses BERT to convert text descriptions into embeddings, which are then fed into the Generator and Discriminator models for training

* The Generator creates images conditioned on random noise and text embeddings, while the Discriminator classifies them as real or fake

* Trains on the CIFAR-10 dataset with paired captions to generate 32x32 RGB images based on the textual descriptions

* The text-to-image synthesis process allows generating images from textual input, e.g., "a red apple on a table"
