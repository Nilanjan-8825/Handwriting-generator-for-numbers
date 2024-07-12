# Handwriting Number Generator using GAN

This repository contains the implementation of a Generative Adversarial Network (GAN) that generates handwritten digits similar to those found in the MNIST dataset.

## Introduction

This project implements a GAN to generate realistic handwritten digits. The GAN consists of two neural networks, the Generator and the Discriminator, which are trained together. The Generator creates fake images, and the Discriminator evaluates them against real images, pushing the Generator to improve its output.

## Dataset

I used the [MNIST](http://yann.lecun.com/exdb/mnist/) dataset, which contains 60,000 training images and 10,000 test images of handwritten digits (0-9).

### Generator
The Generator takes a random noise vector as input and produces a 1x32x32 grayscale image.

### Discriminator
The Discriminator takes an image (real or generated) as input and outputs a probability indicating whether the image is real or fake.
