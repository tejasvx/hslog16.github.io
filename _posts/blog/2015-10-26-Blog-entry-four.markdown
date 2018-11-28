---
layout: post
title:  "Deep Photo Enhancer: Unpaired Learning for Image Enhancement From Photographs With GANs"
date:   2018-11-22 16:51:11
categories: blog
---

In this blog we would look into a recent paper submitted by Yu-Sheng Chen, Yu-Ching Wang, Man-Hsin Kao and Yung-Yu Chuang on deep photo enhancer.

If we look into the previous approaches for photo enhancement histogram equation, background suppressed fuzzy contrast enhancement (used for CT images), log transform, etc have been commonly used.

This paper uses a totally different approach where it combines 2 different aspects of deep learning to provide better results for image enhancement. The 2 major deep learning methods combined here are global U-Net + A-WGAN. WGAN is a kind of 
![alt text](https://www.colorexpertsbd.com/wp-content/uploads/2017/05/Color-Correction-Editing.jpg)
