# Dog-Breed-Classifier
Capstone project for the _Udacity's Machine Learning Engineer_ Nanodegree Program

## Project Overview
The aim of the project is to build a pipeline to process real-world, user-supplied images. A CNN will identify an estimate of the dog's breed, given an image. When the image is of a human, the CNN will choose an estimate of a dog breed that resembles the human. If neither a dog or a human is detected, then an error message is output. Therefore, the models in place should be capable of detecting a dog or human in an image beforehand and then, classify the dog to its breed or a human to the dog breed that s/he resembles.

## Software and Libraries
This project uses Python 3 and is designed to be completed through the Jupyter Notebook IDE. The following libraries are used in this project:  
* numpy
* opencv-python
* matplotlib
* tqdm
* torch
* torchvision

## Project Setup
1. Clone the repo
2. Install pipenv
```
pip install pipenv
```
3. cd to the project directory
4. Create the virtual environment
```
pipenv install --skip-lock
```
5. Activate the virtual environment
```
pipenv shell
```
6. Create a directory named 'data' in this project's home directory
```
mkdir data
```
7. Download the dataset provided by Udacity.  

* Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it at the location `data/dog_images`. 

* Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip).  Unzip the folder and place it at the location `data/lfw`.

8. Create a directory named `haarcascades`
```
mkdir haarcascades
```
9. Download the pre-trained face detector named `haarcascade_frontalface_alt.xml` from 'https://github.com/opencv/opencv/tree/master/data/haarcascades' and place the xml file inside `haarcascades/`
10. Launch the jupyter notebook
```
pipenv run jupyter notebook
```
