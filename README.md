# sEMG-BASED MULTI-LABEL HAND GESTURE RECOGNITION
This is the code accompaniment for my [Thesis](https://nemertes.library.upatras.gr/items/c0d05b9f-5b20-4dc9-8c1f-4245b1c2c8d2)

## Abstract
The recognition and classification of hand gestures using surface electromyography
(sEMG) has gathered a lot of interest from the research community in recent years. This
is due to its applications in the medical field (prosthetic limbs) as well as its use as a tool
in Human-Computer Interaction. Initially, classical machine learning techniques were
employed to classify these movements, but now, deep learning techniques, specifically
neural networks, are being utilized.
This thesis will investigate whether the combination of Convolutional Neural Networks
(CNNs) and Recurrent Neural Networks (RNNs) can yield better results compared to using
CNNs alone. To ensure comparable experimental results, the CNN architecture used
across all experiments will be kept as consistent as possible. The data used for training
and testing the neural networks were sourced from the publicly available Ninapro
database. The code was developed in Python, and the Keras library was used for building
the models.


## Dependacies 
tensorflow==1.13.1
keras==2.2.4
numpy==1.16.2
scipy==1.2.1
sklearn==0.20.3

## Database
In order to run the code you need to download [Ninapro DB1](https://ninapro.hevs.ch/instructions/DB1.html) and extract it in a folder named Ninapro. In this folder the data of its subject should be in a folder named s1 for the first, s2 for ths second etc.
