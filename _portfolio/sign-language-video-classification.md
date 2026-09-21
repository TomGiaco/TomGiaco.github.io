---
title: "Deep learning for sign language recognition"
excerpt: "Turning sign language videos into 3×3 frame grids so that a CNN can classify them as single images."
collection: portfolio
---

A group project applying deep learning to video classification on the [World-Level American Sign Language (WLASL)](https://www.kaggle.com/datasets/risangbaskoro/wlasl-processed) dataset, where each clip shows a single signed word.

**My contribution** was a convolutional approach that sidesteps video modelling entirely. Rather than processing the clip as a temporal sequence, it extracts 9 frames from the middle of the video and tiles them into a single 3×3 grid image — so the temporal structure of the sign becomes spatial structure in one static picture, and the problem reduces to ordinary image classification.

On top of that representation I built:

* **Data augmentation** suited to video: zoom, speed-up, and horizontal flip.
* **A two-block CNN**, each block being convolution → batch normalisation (batches of 10 images) → average pooling, feeding a dense multi-layer perceptron for the final classification.

**Code:** [github.com/TomGiaco/Deep-Learning-to-predict-Sign-Language](https://github.com/TomGiaco/Deep-Learning-to-predict-Sign-Language)
