---
layout: post
title:  "Batch Normalization"
date:   2018-05-23 11:51:11
categories: blog
---
Why Batch Normalization?

We normalize the input layer , For example if we got some features from 0 to 1 and some from 1 to 1000 , we normalize them to speed up learning. If input is getting benefit then we should do it for the values in hidden layers , they usually change all the times and get 10 times or more improvement in training speed. 

BN reduces the amount by what the hidden unit values shift around (covariance shift). 

Next question : What's covariance shift ? 
Suppose we train our network on black cat images. If we apply it to data of colored cats then it will not work as expected. In other words, if an algorithm learned some X to Y mapping, and if the distribution of X changes, then we might need to retrain the learning algorithm by trying to align the distribution of X with the distribution of Y.

