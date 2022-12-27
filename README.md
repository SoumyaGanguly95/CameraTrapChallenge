# CameraTrapChallenge

(PROJECT UNDER DEVELOPMENT)

## Project Goals

### First Iteration

1. Identify coherent sequences of images (over time) for both Badger and Deer Dataset
2. Locate the animals in the images (rough position)
3. Classify the animals (badger vs. deer)

### Second Iteration

1. Extend the BDD dataset with at least 2 additional species (at least 50 images each, day or day & night) of your choice (called BDD+)
2. Locate the animals in the images (alternative method)
3. Classify the animals into the min. 4 classes (alternative method)

## Project

### Scope: Computer Vision

The target is to achieve the goals using;

1. Analytical Computer Vision Algorithms
2. Machine Learning Algorthms

### Dataset

For this project, terrestrial remote sensing CameraTrap data of a National Park is being used. The dataset used is a part of an active research project and therefore classified. The data folder still exists in the local project repository, however it is intentionally left uncommitted for security reasons.

### Identify coherent sequences of images (over time) for both Badger and Deer Dataset

In order to identify sequences of images, it is necessary to compare two adjacent images in the sequence. If two images are identical or nearly identical, we can consider them to belong to the same sequence. This comparison can also be performed for non-adjacent images. In the scope of this project analytical algorithm like Structural Similarity Index (SSIM) has been used and the accuracy is still under evaluation.
--In Progress--
