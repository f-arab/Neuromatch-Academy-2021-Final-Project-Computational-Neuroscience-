# Overview
This package is a Python code for our final project of Computational Neuroscience course offered by Neuromatch Academy on Summer 2021. 

In this project, we aim at answering the following question: Can a DNN (Deep Convolutional Network) feature-weighted receptive-field (fwRF) encoding model reveal the hierarchical representation of visual features across visual cortex?

We first use an Alexnet model which has been pretrained on ImageNet dataset. We then feed in Kay natural images and store the activations of each layer of Alexnet. For correlation analysis, we feed in multiple images and treat the activations at each node as a time-series. 

Finally, we build some encoding models which can predict the fMRI response of each voxel in visual cortex to kay natural images using the activations of different layers in Alexnet.

Similar hierarchical representations in both Alexnet and visual cortex are observed showing that early layers in Alexnet are more predictive in the response of early visual areas in the brain and the activation of higher layers of Alexnet are more correlated with the fMRI response in higher visual areas of the brain.

# Dependencies
Python, Numpy, Pytorch, Matplotlib, Scikit-learn

# Dataset
[Kay natural images](https://www.youtube.com/watch?v=LdJkLyw4yzg)

# Contact
This is a joint work with my teamates at NMA 2021 Summer School:

- James Brissenden
- Fahimeh Arab
- Dennis Maharjan
- Ming-Ray Liao
- Majid Abbasi

Email me (Fahimeh) at farab002@ucr.edu for further questions or comments.


