# Udacity - Dog Breed Classification using CNNs

This repository holds work related to experiments on building a Dog Breed CNN classifier.

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The project should run on deployments of Python versions 3.*. 
If deploying on a new conda or virtual environment, the following should be enough to execute the notebooks.
* jupyter
* numpy
* pandas
* matplotlib
* sklearn
* keras
* opencv2

## Project Motivation<a name="motivation"></a>

This project was created as part of the assignments of Udacity's Data Science Nanodegree. It amins to create a dob breed classifier based on Convolutional Neural Networks (CNNs).
It receives as input an image (of a dog or a human), and analyzes if the image is of a human or not. If so, it will provide
which dog breed more closely resembles the image provided. If the image resembles a dog, it will try to predict which breed the dog
belongs to.

We provide the notebook for the step-by-step creation of the model in this repository, which will also
contain links to the different pre-trained models used during the process of deciding which model to use as the base for experimenting with the classifier model.
## File Descriptions <a name="files"></a>

The analysis process and results obtained are described in the *Seattle-AirBnb-Project* notebook available here. It showcases the whole process used during the analysis, from data preparation to analysis results. 

## Results<a name="results"></a>

The main findings of the code can be found on the Medium post available [here](https://adaltoc.medium.com/how-professional-renters-fair-in-airbnb-a-data-science-study-1d15b51d2cd5).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

## References
- Code: 
  - The base template code and original images used were provided as part of [Udacity's Data Scientis Nanodegree 
  course](https://www.udacity.com/course/data-scientist-nanodegree--nd025).
  - OpenCV's [pre-trained detectors](https://github.com/opencv/opencv/tree/master/data/haarcascades) based on Haar feature-based cascade classifiers. 
- Images:
  - Additional human images:
  Photos by [Ayo Ogunseinde](https://unsplash.com/@armedshutter?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/people?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
  - Additional dog images: [American Kennel Club website](https://www.akc.org/dog-breeds)

This project is distributed under MIT License.