# ENet-EmdNet
Real-Time Embedded Traffic Sign Recognition Using Efficient Convolutional Neural Network

This is the official PyTorch implementation of our paper: "Real-Time Embedded Traffic Sign Recognition Using Efficient Convolutional Neural Network". 
## Introduction
Traffic sign recognition(TSR) based on deep learning is rapidly developing. Specifically, TSR contains two technologies traffic sign classification (TSC) and traffic sign detection (TSD). However, the challenge of TSR is to ensure its efficiency, which means adequate accuracy, generalization, and speed in real - time by a computationally limited platform. In this paper, we will introduce a new efficient TSC network called ENet (efficient network) and a TSD network called EmdNet (efficient network using multiscale operation and depthwise separable convolution). We used data mining and multiscale operation to improve the accuracy and generalization ability, and used depthwise separable convolution(DSC) to improve the speed. The resulting ENet possesses 0.9M parameters (1/15 the parameters of the start-of-the-art method) while still achieving an accuracy of 98.6% on the German Traffic Sign Recognition benchmark (GTSRB). In addition, we design EmdNet' s backbone network according to the principles of ENet. The EmdNet with the SDD Framework possesses only 6.3M parameters, which is similar to MobileNet' s scale.

![Image text](https://raw.githubusercontent.com/b-xie/ENet-EmdNet-/main/Figure7.png)

![Image text](https://raw.githubusercontent.com/b-xie/ENet-EmdNet-/main/Figure8.png)
