---
title: "SinGAN : Image denoising task using single image GAN (December 2019)"
excerpt: "Paper extension of the [SinGAN](https://arxiv.org/abs/1905.01164) model developed by Google Research and Technion team, to perform image denoising tasks using a Generative Model learned from a Single Natural Image <br/><img src='/images/singan.jpg'>"
collection: portfolio
---

Extension of SinGAN (https://github.com/tamarott/SinGAN) on Image Denoising. This was my final project for the [MVA](https://www.master-mva.com/) course "[Object Recognition and Computer Vision](https://www.di.ens.fr/willow/teaching/recvis19/)" (teached by Jean Ponce, Ivan Laptev, Cordelia Schmid and Josef Sivic), and I was advised by Ignacio Rocco.

The approach was to take advantage of the pyramid of GANs in the SinGAN model and the evolution from the first layers of GANS (coarse image features) to the highest layers (finest image features).

We divided the training into 2 scenarios, by training the our SinGAN model first on a clear version of the image, and later on the noisy one. We described the pros and cons of each of our trials in the [report](https://khaoulabelahsen.github.io/files/singan_report.pdf).

You can find the [final report](https://khaoulabelahsen.github.io/files/singan_report.pdf) for this project and the Python [source code](https://github.com/khaoulabelahsen/SinGAN) which provide further details about this project.
