Generative Adversarial Networks (GANs)
MNIST & Fashion-MNIST Image Generation

This repository contains two GAN implementations built using TensorFlow/Keras to generate synthetic images from noise.
The projects demonstrate how GANs learn data distributions by training a Generator and Discriminator in competition.

Projects Included
  1. GAN on MNIST

    Generates handwritten digits (0–9)
    
    Dataset: MNIST
    
    Output: Realistic digit images (28×28 grayscale)

   2. GAN on Fashion-MNIST

    Generates fashion items (shirts, shoes, bags, etc.)
    
    Dataset: Fashion-MNIST
    
    Output: Synthetic clothing images (28×28 grayscale)

 GAN Concept (Quick Overview)

A Generative Adversarial Network consists of:

Generator

Takes random noise as input

Learns to generate fake images

Discriminator

Distinguishes real images from fake ones

Training continues until the generator produces images that the discriminator can no longer easily classify.
