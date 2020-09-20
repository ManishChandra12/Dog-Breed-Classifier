# Dog-Breed-Classifier

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
