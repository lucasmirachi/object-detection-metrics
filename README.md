# Object Detection Metrics

This is a study repo where, as seen during the [Udacity Self-Driving Car Engineer Nanodegree](https://www.udacity.com/course/self-driving-car-engineer-nanodegree--nd0013), I'll put some class notes and concepts I got during the course and also an example of how to identify, calculate and analyze metrics in a Object Detection problem.

## Concepts

### What is Machine Learning

<center>![](./imgs/img1.png){width=70%}</center>

* **Artificial Intelligence (AI)**: a system that leverages information from its environment to make decision. For example, a video game bot.
* **Machine Learning (ML)**: an AI that does not need to be explicitly programmed and instead learns from data. For example, a spam classification algorithm.
* **Deep Learning (DL)**: a subset of ML algorithms that do not require handcrafted features and can work with raw data. For example, an object detection algorithm with a convolutional neural network.

### Classification Metrics

Knowing that each Machine Learning / Deep Learning problem requires its own metrics, for **Classificaion & Object Detection** problems, it is usually considered the following metrics:

* Precision

```math
PRECISION = {TP \over TP + FP}
```


 
