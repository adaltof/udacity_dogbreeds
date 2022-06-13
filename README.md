# Udacity - Dog Breed Classification using CNNs

This repository holds work related to experiments on building a Dog Breed CNN classifier.

### Table of Contents

2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Support on Environment Preparation](#installation)
6. [Licensing, Authors, and Acknowledgements](#licensing)


## Project Motivation<a name="motivation"></a>

This project was created as part of the assignments of Udacity's Data Science Nanodegree. It amins to create a dob breed classifier based on Convolutional Neural Networks (CNNs).
It receives as input an image (of a dog or a human), and analyzes if the image is of a human or not. If so, it will provide
which dog breed more closely resembles the image provided. If the image resembles a dog, it will try to predict which breed the dog
belongs to.

We provide the notebook for the step-by-step creation of the model in this repository, which will also
contain links to the different pre-trained models used during the process of deciding which model to use as the base for experimenting with the classifier model.
## File Descriptions <a name="files"></a>
The main files and folders contained in this repo are:

- **dog_app.ipynb**: Jupyter notebook presenting all steps from importing dataset, creation of models, and results analysis.
- **haarcascades/**: Folder containing export of Haar featurebased cascade classifiers to import.
- **requirements/**: Folder with requirements for building environments with dependencies.
- **images/**: Set of images used in the jupyter notebook and Medium post article.


## Results<a name="results"></a>

The main findings of the code can be found on the Medium post available [here](https://adaltoc.medium.com/dog-breed-classifier-using-cnns-a50efe95a05b).

## Support on Environment Preparation<a name="installation"></a>
If you require support on preparing the environment to run this project, there is a detailed set of instructions in the [original template code repo](https://github.com/udacity/dog-project#instructions), maintained by Udacity.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
- Code: 
  - The base template code and original images used were provided as part of [Udacity's Data Scientis Nanodegree 
  course](https://www.udacity.com/course/data-scientist-nanodegree--nd025).
  - OpenCV's [pre-trained detectors](https://github.com/opencv/opencv/tree/master/data/haarcascades) based on Haar feature-based cascade classifiers. 
- Images:
  - Additional human images:
  Photos by [Ayo Ogunseinde](https://unsplash.com/@armedshutter?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/people?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
  - Additional dog images: [American Kennel Club website](https://www.akc.org/dog-breeds)

This project is distributed under MIT License.