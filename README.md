# The MotorCyce Detection on Android
The Huge Poject for Mobile Applicaiton "Motor Detection On Android"

## Motivation
hello Guy's we are students from Telkom Universit and the project from major topic Mobile Application that create "Motor Detection on Android Using Tensorflow Library for Android Studio". hmm this topic is very interested for us.

### What Do you think about Machine Learning and Neural Network?

### What Do you think about Tensorflow?
TensorFlow™ is an open source software library for high performance numerical computation. Its flexible architecture allows easy deployment of computation across a variety of platforms (CPUs, GPUs, TPUs), and from desktops to clusters of servers to mobile and edge devices. Originally developed by researchers and engineers from the Google Brain team within Google’s AI organization, it comes with strong support for machine learning and deep learning and the flexible numerical computation core is used across many other scientific domains. You can see [Tensorflow web site](https://www.tensorflow.org/).

### What Do you think about Tensorflow Object Detection API?
Creating accurate machine learning models capable of localizing and identifying multiple objects in a single image remains a core challenge in computer vision. The TensorFlow Object Detection API is an open source framework built on top of TensorFlow that makes it easy to construct, train and deploy object detection models. At Google we’ve certainly found this codebase to be useful for our computer vision needs, and we hope that you will as well.
you can see [Tutorial Tensorflow Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection)

### What Do you think about Library tensorflow for Android Studio?


Before started The project we must install some environment. in this project we use Ubuntu OS for custom our model (motorcycle).  for this project we use environment in anaconda you can see [Anaconda Instalation](https://www.digitalocean.com/community/tutorials/how-to-install-anaconda-on-ubuntu-18-04-quickstart/). After install anaconda you must install some library that you can see [introduce installation](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/installation.md/) for your environment. 


Okay Let's Start The Project
Create Own Dataset "Motorcycle"

**1. Collect Image**

The our dataset use 140 images motorcycle then 100 images for data train and 40 image for data test. the environment image must in 4 pm until 6 pm o'clock.

**2. Anotations Images**

The anotations related about labeling each images. you can use software opensource [labelimg](https://github.com/tzutalin/labelImg).

**3. Create Label Map (.pbtxt)**

Classes need to be listed in the label map. Since we're only detecting motorcycle, the label map should contain only one item like the following
```
item{
  id: 1
  name: 'motor'
}
```
Note that id should start from 1, because 0 is a reserved id. Save this file as label_map.pbtxt in models/annotations/.
## Create Own Dataset "MotorCycle"
