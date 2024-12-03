# vignette-adversarial-attacks

Vignette about adversarial attacks on neural network image classification models; created as a class project for PSTAT 197A in Fall 2024.
Contributors:   Henry Louie, Owen Philliber, Parker Reedy, Edwin Yang, Eric Zhang

Abstract

Adversarial attacks is a technique used to decieve machine learning models by employing "defective" inputs. The result of these altered inputs is the misclassification of the input. Typically these adversarial attack techniques change the inputs in a way that is indistinguishable to the human eye, but causes the model to fail to properly identity the contents of the image. One adversarial attack technique that we focus on is the fast gradient sign method attack. This method uses the gradient of the loss function with respect to the input data to create adversarial inputs. The gradient sign method alters the input by adding a perturbation (distortions) proportional to sign of the gradient, scaled by a small factor. In this repository we use image data from the CIFAR-10 dataset, which contains 60,000 images of 10 different classes. This method of adversarial attacks serves as a foundational approach to studying these attacks and building more durable models. 

Contents

This repository contains two folders, models and img. The first folder to visit is the models folder which contains the Jupyter notes on how to set up a gradient sign method adversarial attack on an image classification model. In this example we use a model with two convolution layers and max pooling and show how the addition of perturbation results in misclassification of the images. For further examples, the img folder contains 5 images of inputs and the models classification before and after applying the gradient sign method. 

References

To learn more about gradient sign method attacks you can follow this example: 
https://www.tensorflow.org/tutorials/generative/adversarial_fgsm

For a more in depth overview of adversarial attacks you can look at this article:
https://arxiv.org/pdf/1412.6572

If you want to check out the dataset we used, follow this link: 
https://www.cs.toronto.edu/~kriz/cifar.html

We also provide a video tutorial on how to download the dataset:
https://www.youtube.com/watch?v=640ipvR0HhQ

Contributing

This repository is for educational use only. The examples we show are followed by other creators, and are used to teach the basics about adverserial attacks. There will be no more additional contributions to this repository.
